# CameraTrack

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraTrack.yml" sourcestartlinenumber="1">A track containing a collection of <xref href="ArcGIS.Desktop.Mapping.CameraKeyframe" data-throw-if-not-resolved="false"></xref> objects that defines the view direction and rotation during the animation.</p>


## Object Signature

```csharp
public sealed class CameraTrack : Track
```


## Members

### CreateKeyframe(Camera, TimeSpan, AnimationTransition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraTrack.yml" sourcestartlinenumber="1">Create a new keyframe.</p>


```csharp
public Keyframe CreateKeyframe(Camera camera, TimeSpan atTime, AnimationTransition transition)
```
### CreateKeyframe(Camera, TimeSpan, AnimationTransition, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraTrack.yml" sourcestartlinenumber="1">Create a new keyframe.</p>


```csharp
public Keyframe CreateKeyframe(Camera camera, TimeSpan atTime, AnimationTransition transition, double transitionScale)
```


