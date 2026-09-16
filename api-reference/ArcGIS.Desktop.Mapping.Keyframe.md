# Keyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Keyframe.yml" sourcestartlinenumber="1">Represents the base class for all keyframe types.</p>


## Object Signature

```csharp
public abstract class Keyframe
```

## Remarks

<p>
    A keyframe is a visual way-point along the animation path in a map or scene. 
    When an animation is played, values such as the location of the camera, the current map time, the current map range, and layer transparencies 
    are interpolated between the stored states defined by the keyframe using a configurable transition type. 
    The transition type defines how frames are interpolated between keyframes.
    </p>
<p>
    For example, let's say we have 2 keyframes in a track one at a time of 0 seconds and the second at a time of 3 seconds. 
    The first keyframe has a value for X of 1 and the second keyframe has a value for X of 5. The second keyframe defines the transition for X as linear. 
    What this means is at 0 seconds in the animation X is 1, at 3 seconds X is 5 and at 1.5 seconds or halfway between the value would be 3. 
    Each keyframe may have one or more values it stores and a corresponding transition definition for each value. 
    </p>


## Members

### TrackTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Keyframe.yml" sourcestartlinenumber="1">Gets or sets the value of time that the keyframe exists in the track.</p>


```csharp
public TimeSpan TrackTime { get; set; }
```


