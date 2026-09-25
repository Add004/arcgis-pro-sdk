# ViewAnimation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Allows control of the frame or time along an animation for the view.</p>


## Object Signature

```csharp
public sealed class ViewAnimation
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Similar to how the map defines the layers that make up the map, the map defines the <xref href="ArcGIS.Desktop.Mapping.Animation" data-throw-if-not-resolved="false"></xref>
and the collection of <xref href="ArcGIS.Desktop.Mapping.Keyframe" data-throw-if-not-resolved="false"></xref> objects for all views of the map.
However, it is possible to have multiple views of a map set to different times or frames in the animation.
An instance of this class is returned from the <xref href="ArcGIS.Desktop.Mapping.MapView.Animation" data-throw-if-not-resolved="false"></xref> property and
can be used to set the current time or frame, step to the next or previous keyframe, or play and stop the animation.</p>


## Members

### BeginExport(string, AnimationExportParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Start exporting an animation.  Subscribe to <xref href="ArcGIS.Desktop.Mapping.Events.AnimationExportFinishedEvent" data-throw-if-not-resolved="false"></xref> to be notified when the export is finished.</p>


```csharp
public bool BeginExport(string animationName, AnimationExportParameters exportParameters)
```
### CurrentFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets and sets current time to specific frame number.</p>


```csharp
public long CurrentFrame { get; set; }
```
### CurrentTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets and sets the playback position of the animation.</p>


```csharp
public TimeSpan CurrentTime { get; set; }
```
### GetCameraAtTime(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets the camera at the specified time in the track. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Camera GetCameraAtTime(TimeSpan time)
```
### GetCurrentRangeAtTime(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets the map range at the specified time in the track. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Range GetCurrentRangeAtTime(TimeSpan time)
```
### GetCurrentTimeAtTime(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets the map time at the specified time in the track. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TimeRange GetCurrentTimeAtTime(TimeSpan time)
```
### GetIsExporting()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets if an animation export is in progress for this map.</p>


```csharp
public bool GetIsExporting()
```
### GetIsVisibleAtTime(Layer, TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets a value that indicates if the layer is visible at the specified time in the track. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsVisibleAtTime(Layer layer, TimeSpan time)
```
### GetTransparencyAtTime(Layer, TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Gets the transparency of a layer at a specified time in the track. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetTransparencyAtTime(Layer layer, TimeSpan time)
```
### NextKeyframe()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Sets the current time to the time of the next Keyframe.</p>


```csharp
public void NextKeyframe()
```
### Play()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Play the animation.</p>


```csharp
public void Play()
```
### PreviousKeyframe()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Sets the current time to the time of the previous Keyframe.</p>


```csharp
public void PreviousKeyframe()
```
### Stop()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Stop playing the animation.</p>


```csharp
public void Stop()
```
### StopExport()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewAnimation.yml" sourcestartlinenumber="1">Stop exporting, but keep any files that have already been created for the export.</p>


```csharp
public void StopExport()
```


