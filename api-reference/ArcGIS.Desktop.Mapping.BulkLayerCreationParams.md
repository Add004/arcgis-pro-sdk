# BulkLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create multiple layers with pre-defined properties.
See <xref href="ArcGIS.Desktop.Mapping.LayerFactory.CreateLayers(ArcGIS.Desktop.Mapping.BulkLayerCreationParams%2cArcGIS.Desktop.Mapping.ILayerContainerEdit)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class BulkLayerCreationParams : BulkMapMemberCreationParams
```


## Members

### BulkLayerCreationParams(IEnumerable&lt;CIMDataConnection&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public BulkLayerCreationParams(IEnumerable<CIMDataConnection> dataConnections)
```
### BulkLayerCreationParams(IEnumerable&lt;CIMLayerDocument&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public BulkLayerCreationParams(IEnumerable<CIMLayerDocument> layerDocuments)
```
### BulkLayerCreationParams(IEnumerable&lt;Item&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public BulkLayerCreationParams(IEnumerable<Item> items)
```
### BulkLayerCreationParams(IEnumerable&lt;LayerCreationParams&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Desktop.Mapping.LayerCreationParams" data-throw-if-not-resolved="false"></xref>.
The LayerCreationParams objects must be sourced as all Uris or all CIMDataConnections or all Items.
Supplying a combination of these will cause <xref href="ArcGIS.Desktop.Mapping.LayerFactory.CreateLayers(ArcGIS.Desktop.Mapping.BulkLayerCreationParams%2cArcGIS.Desktop.Mapping.ILayerContainerEdit)" data-throw-if-not-resolved="false"></xref>
to throw an ArgumentException.</p>


```csharp
public BulkLayerCreationParams(IEnumerable<LayerCreationParams> layerCreationParams)
```
### BulkLayerCreationParams(IEnumerable&lt;Uri&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public BulkLayerCreationParams(IEnumerable<Uri> uris)
```
### AutoZoomOnEmptyMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets if the Map is zoomed to the combined extent of the layers if they are the
first set of layers to be added to the Map.  The default value is true.</p>


```csharp
public bool AutoZoomOnEmptyMap { get; set; }
```
### ExpandedState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets the layer expanded state for all layers. Default value is <xref href="ArcGIS.Desktop.Mapping.LayerExpandedState.Default" data-throw-if-not-resolved="false"></xref>
meaning that the expanded state of the layer is set according to the layer type.
On creation, some layer types are expanded by default (for example FeatureLayers,
CatalogLayers, TopologyLayers); other layer types are collapsed by default (for example TinLayers,
TerrainLayers, ParcelLayers).</p>


```csharp
public LayerExpandedState ExpandedState { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets layer visibility for all layers.  The default value is null meaning visibility is set according to the
<xref href="ArcGIS.Desktop.Core.MappingOptions.NewLayersVisible" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
public bool? IsVisible { get; set; }
```
### MapMemberIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets the index of the first layer in the map or group layer. All subsequent layers added
will follow this first layer.
<xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams.MapMemberPosition" data-throw-if-not-resolved="false"></xref> must be set to <xref href="ArcGIS.Desktop.Mapping.MapMemberPosition.Index" data-throw-if-not-resolved="false"></xref> for this value to honored.
If <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams.MapMemberPosition" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Desktop.Mapping.MapMemberPosition.Index" data-throw-if-not-resolved="false"></xref> and this value is <b>NOT</b>
set, then the behavior will revert to auto arrange.</p>


```csharp
public int MapMemberIndex { get; set; }
```
### MapMemberPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets the mapMember position.<br>
Specifies whether the mapMember should be auto positioned or be on the top or at the bottom.
Default value is <xref href="ArcGIS.Desktop.Mapping.MapMemberPosition.AutoArrange" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapMemberPosition MapMemberPosition { get; set; }
```
### RollbackBehavior

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets the rollback behavior of the <xref href="ArcGIS.Desktop.Mapping.LayerFactory.CreateLayers(ArcGIS.Desktop.Mapping.BulkLayerCreationParams%2cArcGIS.Desktop.Mapping.ILayerContainerEdit)" data-throw-if-not-resolved="false"></xref> method.
This property only applies if the <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams" data-throw-if-not-resolved="false"></xref> is created with
<xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams.%23ctor(System.Collections.Generic.IEnumerable%7bArcGIS.Desktop.Mapping.LayerCreationParams%7d)" data-throw-if-not-resolved="false"></xref>, otherwise it is ignored.
Default value is <xref href="ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.NoRollback" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LayerCreationRollbackBehavior RollbackBehavior { get; set; }
```
### ServiceCustomParameters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets custom parameters that are appended to the URL of all requests related to a service layer.</p>


```csharp
public Dictionary<string, string> ServiceCustomParameters { get; set; }
```


