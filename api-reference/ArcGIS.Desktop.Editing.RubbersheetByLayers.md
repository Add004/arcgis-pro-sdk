# RubbersheetByLayers

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByLayers.yml" sourcestartlinenumber="1">Perform a rubbersheet operation using geometries from specified layers.</p>


## Object Signature

```csharp
public sealed class RubbersheetByLayers : RubbersheetMethod
```


## Members

### RubbersheetByLayers()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByLayers.yml" sourcestartlinenumber="1">Constructs a new <xref href="ArcGIS.Desktop.Editing.RubbersheetByLayers" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public RubbersheetByLayers()
```
### AnchorPointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByLayers.yml" sourcestartlinenumber="1">Gets or sets the layer containing points to be used as anchor points for the rubbersheet.</p>


```csharp
public Layer AnchorPointLayer { get; set; }
```
### LimitedAdjustmentAreaLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByLayers.yml" sourcestartlinenumber="1">Gets or sets the layer containing polygons to be used to limit the features in the rubbersheet operation.</p>


```csharp
public Layer LimitedAdjustmentAreaLayer { get; set; }
```
### LinkLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByLayers.yml" sourcestartlinenumber="1">Gets or sets the layer containing the lines used as vectors for the rubbersheet.</p>


```csharp
public Layer LinkLayer { get; set; }
```


