# CIMKeyframeCamera

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Represents a camera keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeCamera : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">The camera keyframe stores the value of the camera and defines the transitions for each of the values of the camera.</p>


## Members

### CIMKeyframeCamera()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Represents a camera keyframe.</p>


```csharp
public CIMKeyframeCamera()
```
### AdjustedCameraPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the bezier control points between the previous camera position and the current camera position. Used to define the camera path for the AdjustableArc transition. When the value is null or empty, a default path is used. Must be in the map's spatial reference.</p>


```csharp
public Multipoint AdjustedCameraPath { get; set; }
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the camera for the keyframe.</p>


```csharp
public CIMViewCamera Camera { get; set; }
```
### CameraTransitionMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the transition mode determines whether the camera path follows a Geodesic or Cartesian interpolation.</p>


```csharp
public esriAnimationTransitionMode CameraTransitionMode { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeCamera.</p>


```csharp
public CIMKeyframeCamera Clone()
```
### FieldOfView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the field of view angle. Only applies to scene views.</p>


```csharp
public double FieldOfView { get; set; }
```
### FieldOfViewTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the field of view of the camera.</p>


```csharp
public AnimationTransition FieldOfViewTransition { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeCamera with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeCamera FromJson(string json, JsonDeserializationSettings settings = null)
```
### HeadingTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the heading of the camera.</p>


```csharp
public AnimationTransition HeadingTransition { get; set; }
```
### LookAt

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets a geometry for the camera to look at. When a geometry is set it overrides the camera's heading and pitch. Must be in the map's spatial reference.</p>


```csharp
public Geometry LookAt { get; set; }
```
### PitchTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the pitch of the camera.</p>


```csharp
public AnimationTransition PitchTransition { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RollTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the roll of the camera.</p>


```csharp
public AnimationTransition RollTransition { get; set; }
```
### ScaleTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the scale of the camera.</p>


```csharp
public AnimationTransition ScaleTransition { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeCamera and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TransitionScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the value of adjustable transitions. The value must be between 0.0 and 1.0. Smaller values will result in a tighter / smaller curve than larger values.</p>


```csharp
public double TransitionScale { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the x of the camera.</p>


```csharp
public AnimationTransition XTransition { get; set; }
```
### YTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the y of the camera.</p>


```csharp
public AnimationTransition YTransition { get; set; }
```
### ZTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeCamera.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the z of the camera.</p>


```csharp
public AnimationTransition ZTransition { get; set; }
```


