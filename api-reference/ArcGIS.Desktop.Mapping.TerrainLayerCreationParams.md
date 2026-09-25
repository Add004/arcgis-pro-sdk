# TerrainLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a <xref href="ArcGIS.Desktop.Mapping.TerrainLayer" data-throw-if-not-resolved="false"></xref> with pre-defined properties.</p>


## Object Signature

```csharp
public class TerrainLayerCreationParams : LayerCreationParams
```


## Members

### TerrainLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainLayerCreationParams(CIMDataConnection dataConnection)
```
### TerrainLayerCreationParams(Terrain)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainLayerCreationParams(Terrain terrain)
```
### TerrainLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainLayerCreationParams(Item item)
```
### TerrainLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TerrainLayerCreationParams(Uri uri)
```
### RendererDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a dictionary of <xref href="ArcGIS.Desktop.Mapping.TinRendererDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Dictionary<SurfaceRendererTarget, TinRendererDefinition> RendererDefinitions { get; set; }
```
### Terrain

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Terrain Terrain { get; protected set; }
```


