# LayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a layer with pre-defined properties such as minimum and maximum scales, visibility etc.</p>


## Object Signature

```csharp
public class LayerCreationParams : MapMemberCreationParams
```


## Members

### LayerCreationParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
protected LayerCreationParams()
```
### LayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LayerCreationParams(CIMDataConnection dataConnection)
```
### LayerCreationParams(CIMLayerDocument)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LayerCreationParams(CIMLayerDocument layerDoc)
```
### LayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LayerCreationParams(Item item)
```
### LayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LayerCreationParams(Uri uri)
```
### AutoZoomOnEmptyMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets if the Map is zoomed to the layer extent if it is the first
layer to be added.</p>


```csharp
public bool AutoZoomOnEmptyMap { get; set; }
```
### CreateFromDataConnection(ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a layer with pre-defined properties such as minimum and maximum scales, visibility etc.</p>


```csharp
protected Layer CreateFromDataConnection(ILayerContainerEdit container, int index)
```
### CreateFromItem(ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a layer with pre-defined properties such as minimum and maximum scales, visibility etc.</p>


```csharp
protected Layer CreateFromItem(ILayerContainerEdit container, int index)
```
### CreateFromLayerDocument(ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a layer with pre-defined properties such as minimum and maximum scales, visibility etc.</p>


```csharp
protected Layer CreateFromLayerDocument(ILayerContainerEdit mapOrGroupLayer, int index)
```
### CreateFromURI(ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a layer with pre-defined properties such as minimum and maximum scales, visibility etc.</p>


```csharp
protected Layer CreateFromURI(ILayerContainerEdit container, int index)
```
### CreateLayerImpl(ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a layer with pre-defined properties such as minimum and maximum scales, visibility etc.</p>


```csharp
protected Layer CreateLayerImpl(ILayerContainerEdit mapOrGroupLayer, int layerIndex)
```
### ExpandedState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets the layer expanded state.  Default value is <xref href="ArcGIS.Desktop.Mapping.LayerExpandedState.Default" data-throw-if-not-resolved="false"></xref>
meaning that the expanded state of the layer is set according to the layer type.</p>


```csharp
public LayerExpandedState ExpandedState { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets layer visibility. Default value is null meaning that the layer visibility
is set according to <xref href="ArcGIS.Desktop.Core.MappingOptions.NewLayersVisible" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool? IsVisible { get; set; }
```
### MaximumScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets layer maximum scale. Default value is null meaning that the MaximumScale is not set.</p>


```csharp
public double? MaximumScale { get; set; }
```
### MinimumScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets layer minimum scale.  Default value is null meaning that the MinimumScale is not set.</p>


```csharp
public double? MinimumScale { get; set; }
```
### ServiceCustomParameters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets custom parameters that are appended to the URL of all requests related to a service layer.</p>


```csharp
public Dictionary<string, string> ServiceCustomParameters { get; set; }
```


