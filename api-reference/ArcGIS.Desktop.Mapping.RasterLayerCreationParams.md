# RasterLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a raster layer with pre-defined properties such as colorizer, visibility etc.</p>


## Object Signature

```csharp
public class RasterLayerCreationParams : LayerCreationParams
```


## Members

### RasterLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterLayerCreationParams(CIMDataConnection dataConnection)
```
### RasterLayerCreationParams(RasterDataset)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.RasterDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterLayerCreationParams(RasterDataset rasterDataset)
```
### RasterLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterLayerCreationParams(Item item)
```
### RasterLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterLayerCreationParams(Uri uri)
```
### ColorizerDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a <xref href="ArcGIS.Desktop.Mapping.RasterColorizerDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterColorizerDefinition ColorizerDefinition { get; set; }
```
### RasterDataset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayerCreationParams.yml" sourcestartlinenumber="1">Gest the <xref href="ArcGIS.Core.Data.Raster.RasterDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterDataset RasterDataset { get; protected set; }
```


