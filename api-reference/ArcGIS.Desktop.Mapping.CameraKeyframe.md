# CameraKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Represents a keyframe in the <xref href="ArcGIS.Desktop.Mapping.CameraTrack" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class CameraKeyframe : Keyframe
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">The camera keyframe stores the value of the camera and defines the transitions for each of the values of the camera.</p>


## Members

### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the camera for the keyframe.</p>


```csharp
public Camera Camera { get; set; }
```
### FieldOfView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the value indicating the field of view angle. Only used in scene views.</p>


```csharp
public double FieldOfView { get; set; }
```
### FieldOfViewTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the transition for the field of view of the camera.</p>


```csharp
public AnimationTransition FieldOfViewTransition { get; set; }
```
### HeadingTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the transition for the heading of the camera.</p>


```csharp
public AnimationTransition HeadingTransition { get; set; }
```
### PitchTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the pitch of the camera.</p>


```csharp
public AnimationTransition PitchTransition { get; set; }
```
### RollTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the roll of the camera.</p>


```csharp
public AnimationTransition RollTransition { get; set; }
```
### ScaleTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the scale of the camera.</p>


```csharp
public AnimationTransition ScaleTransition { get; set; }
```
### TransitionMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the value indicating that transitions will use a Geodesic (spherical) algorithm or a Cartesian (rectangular) algorithm.</p>


```csharp
public esriAnimationTransitionMode TransitionMode { get; set; }
```
### TransitionScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the value indicating the shape of the curve for adjustable transitions. The value must be between 0.0 and 1.0.
Smaller values will result in a tighter / smaller curve than larger values.</p>


```csharp
public double TransitionScale { get; set; }
```
### XTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the transition for the x value of the camera.</p>


```csharp
public AnimationTransition XTransition { get; set; }
```
### YTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the transition for the y value of the camera.</p>


```csharp
public AnimationTransition YTransition { get; set; }
```
### ZTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CameraKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the z value of the camera.</p>


```csharp
public AnimationTransition ZTransition { get; set; }
```


