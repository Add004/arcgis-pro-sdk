# TinLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a <xref href="ArcGIS.Desktop.Mapping.TinLayer" data-throw-if-not-resolved="false"></xref> with pre-defined properties.</p>


## Object Signature

```csharp
public class TinLayerCreationParams : LayerCreationParams
```


## Members

### TinLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinLayerCreationParams(CIMDataConnection dataConnection)
```
### TinLayerCreationParams(TinDataset)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinLayerCreationParams(TinDataset tinDS)
```
### TinLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinLayerCreationParams(Item item)
```
### TinLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinLayerCreationParams(Uri uri)
```
### RendererDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a dictionary of <xref href="ArcGIS.Desktop.Mapping.TinRendererDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Dictionary<SurfaceRendererTarget, TinRendererDefinition> RendererDefinitions { get; set; }
```
### TinDataset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinDataset TinDataset { get; protected set; }
```


