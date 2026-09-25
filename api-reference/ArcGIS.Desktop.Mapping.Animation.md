# Animation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Represents the collection of tracks, keyframes and transitions that define an animation for the map.</p>


## Object Signature

```csharp
public sealed class Animation
```

## Remarks

<p>Animation is the process of creating a collection of sequential images and playing them back quickly to create an illusion of movement. 
    Each image, just like a picture you take with a camera, marks a significant instance in time, and is called a keyframe. 
    In ArcGIS Pro, animations are authored by defining a set of keyframes that the system uses to create interpolated intermediate frames. 
    Animations can interpolate the camera position, map time, map range, and layer visibility and transparency.</p>
<p>An instance of this class is returned from the <xref href="ArcGIS.Desktop.Mapping.Map.Animation" data-throw-if-not-resolved="false"></xref> property 
    and can be used to manipulate the state of the animation by creating, editing and deleting keyframes.</p>


## Members

### AnimationNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Gets the names of all animations on this map.</p>


```csharp
public string[] AnimationNames { get; }
```
### CurrentAnimationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Gets and sets the active animation.</p>


```csharp
public string CurrentAnimationName { get; set; }
```
### Duration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Gets the length of time of all tracks in the animation.</p>


```csharp
public TimeSpan Duration { get; }
```
### GetDisconnectedTracks()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Gets a disconnected copy of the list of <xref href="ArcGIS.Desktop.Mapping.Animation.Tracks" data-throw-if-not-resolved="false"></xref> in the animation.
Changes to this list are ignored until the list is set to the <xref href="ArcGIS.Desktop.Mapping.Animation.Tracks" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
public List<Track> GetDisconnectedTracks()
```
### NumberOfFrames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Gets the total number of frames in the animation.</p>


```csharp
public long NumberOfFrames { get; }
```
### ScaleDuration(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Adjust the length of the animation by a given scale factor.</p>


```csharp
public void ScaleDuration(double factor)
```
### ScaleDuration(TimeSpan, TimeSpan, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Adjust the length of the track by a given scale factor.</p>


```csharp
public void ScaleDuration(TimeSpan start, TimeSpan end, double factor)
```
### Tracks

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Animation.yml" sourcestartlinenumber="1">Gets and sets the list of tracks in the animation.</p>


```csharp
public List<Track> Tracks { get; set; }
```


