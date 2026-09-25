# LayerTrack

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerTrack.yml" sourcestartlinenumber="1">A track containing a collection of <xref href="ArcGIS.Desktop.Mapping.LayerKeyframe" data-throw-if-not-resolved="false"></xref> objects that defines the visibility and transparency of layers during the animation.</p>


## Object Signature

```csharp
public sealed class LayerTrack : Track
```


## Members

### CreateKeyframe(Layer, TimeSpan, bool, double, AnimationTransition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerTrack.yml" sourcestartlinenumber="1">Create a new keyframe.</p>


```csharp
public Keyframe CreateKeyframe(Layer layer, TimeSpan atTime, bool isVisibile, double transparency, AnimationTransition transition)
```


