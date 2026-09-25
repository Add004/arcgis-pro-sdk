# CIMMapView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Represents a map view in the project.</p>


## Object Signature

```csharp
public class CIMMapView : CIMView, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Represents a map view in the project.</p>


```csharp
public CIMMapView()
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the camera of the view.</p>


```csharp
public CIMViewCamera Camera { get; set; }
```
### CameraEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the camera effect definition for the scene.</p>


```csharp
public CIMCameraEffect CameraEffect { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapView.</p>


```csharp
public CIMMapView Clone()
```
### ColorVisionDeficiencyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the color vision deficiency mode of the view.</p>


```csharp
public ColorVisionDeficiencyType ColorVisionDeficiencyMode { get; set; }
```
### ExploratoryAnalysis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the exploratory analysis definitions for the view.</p>


```csharp
public CIMExploratoryAnalysisDefinition[] ExploratoryAnalysis { get; set; }
```
### FieldOfView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the scene's field-of-view in degrees (value must be between 35 and 70).
Only used when the scene is in Perspective draw mode.</p>


```csharp
public double FieldOfView { get; set; }
```
### FloorFilterSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the floor filter settings of the view.</p>


```csharp
public CIMFloorFilterSettings FloorFilterSettings { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Reconstructs the CIMMapView with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapView FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerRanges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the layer ranges of the view.</p>


```csharp
public CIMLayerRange[] LayerRanges { get; set; }
```
### PauseAnimatedSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether all animated symbol playback is in paused state for the view.</p>


```csharp
public bool PauseAnimatedSymbols { get; set; }
```
### PauseDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether drawing is in paused state for the view.</p>


```csharp
public bool PauseDrawing { get; set; }
```
### PostprocessingEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the post-processing effect definitions for the scene.</p>


```csharp
public CIMPostprocessingEffect[] PostprocessingEffects { get; set; }
```
### RangeSliderSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the range slider settings of the view.</p>


```csharp
public CIMSliderSettings RangeSliderSettings { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SceneDrawingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the scene's drawing mode.</p>


```csharp
public SceneDrawingMode SceneDrawingMode { get; set; }
```
### TimeDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the map time display of the view.</p>


```csharp
public CIMMapTimeDisplay TimeDisplay { get; set; }
```
### TimeSliderSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the time slider settings of the view.</p>


```csharp
public CIMSliderSettings TimeSliderSettings { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapView and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalExaggerationScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the vertical exaggeration of the view.</p>


```csharp
public double VerticalExaggerationScaleFactor { get; set; }
```
### ViewingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the map viewing mode of the view.</p>


```csharp
public MapViewingMode ViewingMode { get; set; }
```
### VisualEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Gets or sets the visual effect definition for the scene.</p>


```csharp
public CIMVisualEffect VisualEffect { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


