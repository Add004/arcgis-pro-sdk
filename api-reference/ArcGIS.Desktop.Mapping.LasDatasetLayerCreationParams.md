# LasDatasetLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer" data-throw-if-not-resolved="false"></xref> with pre-defined properties.</p>


## Object Signature

```csharp
public class LasDatasetLayerCreationParams : LayerCreationParams
```


## Members

### LasDatasetLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasDatasetLayerCreationParams(CIMDataConnection dataConnection)
```
### LasDatasetLayerCreationParams(LasDataset)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasDatasetLayerCreationParams(LasDataset lasDS)
```
### LasDatasetLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasDatasetLayerCreationParams(Item item)
```
### LasDatasetLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasDatasetLayerCreationParams(Uri uri)
```
### LasDataset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasDataset LasDataset { get; protected set; }
```
### RendererDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a dictionary of <xref href="ArcGIS.Desktop.Mapping.TinRendererDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Dictionary<SurfaceRendererTarget, TinRendererDefinition> RendererDefinitions { get; set; }
```


