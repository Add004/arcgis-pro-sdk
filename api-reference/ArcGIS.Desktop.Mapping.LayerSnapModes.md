# LayerSnapModes

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Snap modes for a layer.</p>


## Object Signature

```csharp
public sealed class LayerSnapModes
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Use the properties on this class to determine the snap modes for a layer. Set the snap modes on the layer with the Snapping.SetLayerSnapModes method.</p>


## Members

### LayerSnapModes(LayerSnapModes)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Snap modes for a layer. Makes a copy of the <code class="paramref">layerSnapModes</code>.</p>


```csharp
public LayerSnapModes(LayerSnapModes layerSnapModes)
```
### LayerSnapModes(bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Snap modes for a layer.</p>


```csharp
public LayerSnapModes(bool setAll = false)
```
### Edge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the edge snap mode.</p>


```csharp
public bool Edge { get; set; }
```
### End

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the end snap mode.</p>


```csharp
public bool End { get; set; }
```
### Face

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the face snap mode.</p>


```csharp
public bool Face { get; set; }
```
### GetSnapMode(SnapMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets the state of a single <xref href="ArcGIS.Desktop.Mapping.SnapMode?text=SnapMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool GetSnapMode(SnapMode snapMode)
```
### Intersection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the intersection snap mode.</p>


```csharp
public bool Intersection { get; set; }
```
### Midpoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the midpoint snap mode.</p>


```csharp
public bool Midpoint { get; set; }
```
### Point

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the point snap mode.</p>


```csharp
public bool Point { get; set; }
```
### SetSnapMode(SnapMode, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Sets the state of a single <xref href="ArcGIS.Desktop.Mapping.SnapMode?text=SnapMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetSnapMode(SnapMode snapMode, bool isSet)
```
### Tangent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the tangent snap mode.</p>


```csharp
public bool Tangent { get; set; }
```
### Vertex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerSnapModes.yml" sourcestartlinenumber="1">Gets or sets the vertex snap mode.</p>


```csharp
public bool Vertex { get; set; }
```


