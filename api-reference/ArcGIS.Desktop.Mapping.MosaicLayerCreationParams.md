# MosaicLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a mosaic layer with pre-defined properties such as visibility etc..</p>


## Object Signature

```csharp
public class MosaicLayerCreationParams : LayerCreationParams
```


## Members

### MosaicLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MosaicLayerCreationParams(CIMDataConnection dataConnection)
```
### MosaicLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MosaicLayerCreationParams(Item item)
```
### MosaicLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MosaicLayerCreationParams(Uri uri)
```
### ColorizerDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a <xref href="ArcGIS.Desktop.Mapping.RasterColorizerDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RasterColorizerDefinition ColorizerDefinition { get; set; }
```


