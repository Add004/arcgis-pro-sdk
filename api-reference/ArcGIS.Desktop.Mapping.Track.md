# Track

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">Represents the base class for all track types.</p>


## Object Signature

```csharp
public abstract class Track
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">A track stores the collection of keyframes whose values and transitions define the interpolated values for each frame of the animation.
The <xref href="ArcGIS.Desktop.Mapping.Animation.Tracks" data-throw-if-not-resolved="false"></xref> property for the animation always returns 4 tracks: a <xref href="ArcGIS.Desktop.Mapping.CameraTrack" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Desktop.Mapping.LayerTrack" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Desktop.Mapping.TimeTrack" data-throw-if-not-resolved="false"></xref> and a <xref href="ArcGIS.Desktop.Mapping.RangeTrack" data-throw-if-not-resolved="false"></xref>.
Each track type stores a corresponding keyframe for that type and is used to animate either the camera position, map time, map range, or layer visibility and transparency.
The duration of the animation is equal to the time of the last keyframe in all tracks. The animation is removed from the map by deleting all keyframes in all tracks.</p>


## Members

### AnimationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">Gets and sets the name for this set of tracks.</p>


```csharp
public string AnimationName { get; set; }
```
### DeleteKeyframe(Keyframe)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">Delete a specified keyframe from the track.</p>


```csharp
public void DeleteKeyframe(Keyframe keyframe)
```
### DeleteKeyframe(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">Delete a keyframe at a specified index.</p>


```csharp
public void DeleteKeyframe(int index)
```
### DeleteKeyframe(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">Delete keyframes between a start and end index.</p>


```csharp
public void DeleteKeyframe(int start, int end)
```
### Keyframes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Track.yml" sourcestartlinenumber="1">Gets the collection of keyframes for the track.</p>


```csharp
public IReadOnlyList<Keyframe> Keyframes { get; }
```


