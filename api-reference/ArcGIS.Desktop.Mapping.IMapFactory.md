# IMapFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Map Factory interface for creating maps. See <xref href="ArcGIS.Desktop.Mapping.MapFactory" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public interface IMapFactory
```


## Members

### CanConvertMap(Map, MapConversionType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Determines whether the map can be converted to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool CanConvertMap(Map map, MapConversionType convertTo)
```
### CanConvertMapFromItem(MapProjectItem, MapConversionType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Determines whether the map item can be converted to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool CanConvertMapFromItem(MapProjectItem mapItem, MapConversionType convertTo)
```
### CanCreateMapFrom(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Determines whether a map can be created from an Item.</p>


```csharp
bool CanCreateMapFrom(Item item)
```
### ConvertMap(Map, MapConversionType, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Convert the input map to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map ConvertMap(Map map, MapConversionType convertTo, bool openView)
```
### ConvertMapFromItem(MapProjectItem, MapConversionType, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Convert the input map item to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map ConvertMapFromItem(MapProjectItem mapItem, MapConversionType convertTo, bool openView)
```
### CopyMap(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Copies the input map and adds it to the project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CopyMap(Map map)
```
### CreateLinkChart(string, KnowledgeGraph, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph datastore.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateLinkChart(string name, KnowledgeGraph knowledgeGraph, KnowledgeGraphLayerIDSet idSet)
```
### CreateLinkChart(string, KnowledgeGraph, KnowledgeGraphLayerIDSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph datastore.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateLinkChart(string name, KnowledgeGraph knowledgeGraph, KnowledgeGraphLayerIDSet idSet, string templateLinkChartPath)
```
### CreateLinkChart(string, Uri, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateLinkChart(string name, Uri knowledgeGraphServiceUri, KnowledgeGraphLayerIDSet idSet)
```
### CreateLinkChart(string, Uri, KnowledgeGraphLayerIDSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateLinkChart(string name, Uri knowledgeGraphServiceUri, KnowledgeGraphLayerIDSet idSet, string templateLinkChartPath)
```
### CreateLocalBasemap(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a local basemap of MapType.Basemap <xref href="ArcGIS.Core.CIM.MapType" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateLocalBasemap(string name)
```
### CreateMap(string, MapType, MapViewingMode, Basemap)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateMap(string name, MapType mapType = 0, MapViewingMode defaultViewingMode = 0, Basemap basemap = Basemap.ProjectDefault)
```
### CreateMap(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project from a map package or file Uri.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateMap(Uri dataUri)
```
### CreateMapFromItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project using an item e.g. webmap, mxd etc. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateMapFromItem(Item item)
```
### CreateMapFromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Map CreateMapFromJson(string json)
```
### CreateScene(string, Uri, MapViewingMode, Basemap)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapFactory.yml" sourcestartlinenumber="1">Creates a map of type MapType.Scene <xref href="ArcGIS.Core.CIM.MapType" data-throw-if-not-resolved="false"></xref> with a specified ground elevation source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Map CreateScene(string name, Uri groundElevationSourceUri = null, MapViewingMode defaultViewingMode = 1, Basemap basemap = Basemap.ProjectDefault)
```


