# LayerKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerKeyframe.yml" sourcestartlinenumber="1">Represents a keyframe in the <xref href="ArcGIS.Desktop.Mapping.LayerTrack" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LayerKeyframe : Keyframe
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerKeyframe.yml" sourcestartlinenumber="1">The layer keyframe stores the layer, the visibility state and defines the transitions for the visibility of the layer.</p>


## Members

### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerKeyframe.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the layer is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerKeyframe.yml" sourcestartlinenumber="1">Gets the layer.</p>


```csharp
public Layer Layer { get; }
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerKeyframe.yml" sourcestartlinenumber="1">Gets or sets the transparency of the layer.</p>


```csharp
public double Transparency { get; set; }
```
### TransparencyTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the transparency of the layer.</p>


```csharp
public AnimationTransition TransparencyTransition { get; set; }
```


