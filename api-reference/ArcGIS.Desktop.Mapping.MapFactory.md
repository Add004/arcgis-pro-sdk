# MapFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Provides static methods to create maps.</p>


## Object Signature

```csharp
public class MapFactory : IMapFactory
```


## Members

### CanConvertMap(Map, MapConversionType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Determines whether the map can be converted to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanConvertMap(Map map, MapConversionType convertTo)
```
### CanConvertMapFromItem(MapProjectItem, MapConversionType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Determine whether the map item can be converted to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanConvertMapFromItem(MapProjectItem mapItem, MapConversionType convertTo)
```
### CanCreateMapFrom(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Determines whether a map can be created from an Item.</p>


```csharp
public bool CanCreateMapFrom(Item item)
```
### ConvertMap(Map, MapConversionType, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Convert the input map to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map ConvertMap(Map map, MapConversionType convertTo, bool openView)
```
### ConvertMapFromItem(MapProjectItem, MapConversionType, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Convert the input map item to the specified output type. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map ConvertMapFromItem(MapProjectItem mapItem, MapConversionType convertTo, bool openView)
```
### CopyMap(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Copies the input map and adds it to the project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CopyMap(Map map)
```
### CreateLinkChart(string, KnowledgeGraph, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph datastore.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateLinkChart(string name, KnowledgeGraph knowledgeGraph, KnowledgeGraphLayerIDSet idSet)
```
### CreateLinkChart(string, KnowledgeGraph, KnowledgeGraphLayerIDSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph datastore.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateLinkChart(string name, KnowledgeGraph knowledgeGraph, KnowledgeGraphLayerIDSet idSet, string templateLinkChartPath)
```
### CreateLinkChart(string, Uri, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateLinkChart(string name, Uri knowledgeGraphServiceUri, KnowledgeGraphLayerIDSet idSet)
```
### CreateLinkChart(string, Uri, KnowledgeGraphLayerIDSet, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a link chart map (a map of type MapType.LinkChart) with a specified knowledge graph service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateLinkChart(string name, Uri knowledgeGraphServiceUri, KnowledgeGraphLayerIDSet idSet, string templateLinkChartPath)
```
### CreateLocalBasemap(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a local basemap of MapType.Basemap <xref href="ArcGIS.Core.CIM.MapType" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateLocalBasemap(string name)
```
### CreateMap(string, MapType, MapViewingMode, Basemap)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateMap(string name, MapType mapType = 0, MapViewingMode defaultViewingMode = 0, Basemap basemap = Basemap.ProjectDefault)
```
### CreateMap(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project from a map package or file Uri.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateMap(Uri dataUri)
```
### CreateMapFromItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project using an item e.g. webmap, mxd etc. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateMapFromItem(Item item)
```
### CreateMapFromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a new Map in the project.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Map CreateMapFromJson(string json)
```
### CreateScene(string, Uri, MapViewingMode, Basemap)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Creates a map of type MapType.Scene <xref href="ArcGIS.Core.CIM.MapType" data-throw-if-not-resolved="false"></xref> with a specified ground elevation source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map CreateScene(string name, Uri groundElevationSourceUri = null, MapViewingMode defaultViewingMode = 1, Basemap basemap = Basemap.ProjectDefault)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for IMapFactory.</p>


```csharp
public static IMapFactory Instance { get; }
```


