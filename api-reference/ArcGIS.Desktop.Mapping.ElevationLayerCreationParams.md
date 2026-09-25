# ElevationLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create an elevation surface layer with pre-defined properties.</p>


## Object Signature

```csharp
public class ElevationLayerCreationParams : LayerCreationParams
```


## Members

### ElevationLayerCreationParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
public ElevationLayerCreationParams()
```
### ElevationLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ElevationLayerCreationParams(CIMDataConnection sourceLayerDataConnection)
```
### ElevationLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ElevationLayerCreationParams(Item sourceLayerItem)
```
### ElevationLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ElevationLayerCreationParams(Uri elevationSourceUri)
```
### CanCreateElevationSourceLayerFor(Item, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Check if an elevation source layer can be created and added to a given surface based on a given item.</p>


```csharp
public static bool CanCreateElevationSourceLayerFor(Item sourceLayerItem, ElevationSurfaceLayer surfaceLayer)
```
### CanCreateElevationSourceLayerFor(Uri, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Check if an elevation source layer can be created and added to a given surface based on a given URI.</p>


```csharp
public static bool CanCreateElevationSourceLayerFor(Uri elevationSourceUri, ElevationSurfaceLayer surfaceLayer)
```
### ElevationSourceUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationLayerCreationParams.yml" sourcestartlinenumber="1">Gets or sets the layer URI.</p>


```csharp
public Uri ElevationSourceUri { get; set; }
```


