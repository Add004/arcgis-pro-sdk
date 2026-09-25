# CIMSliderSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Represents slider settings.</p>


## Object Signature

```csharp
public class CIMSliderSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSliderSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Represents slider settings.</p>


```csharp
public CIMSliderSettings()
```
### AliasExpressionLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the string containing URI of the layer that contains the alias definition.</p>


```csharp
public string AliasExpressionLayerURI { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSliderSettings.</p>


```csharp
public CIMSliderSettings Clone()
```
### EndValueLocked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the slider's end thumb will not accept mouse events.</p>


```csharp
public bool EndValueLocked { get; set; }
```
### FlipVertically

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the slider is flipped vertically to put larger values at the bottom and smaller values at the top.</p>


```csharp
public bool FlipVertically { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMSliderSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMSliderSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### FullExtentCustomRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the custom full extent used with the custom range full extent option.</p>


```csharp
public CIMRange FullExtentCustomRange { get; set; }
```
### FullExtentLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer used for the full extent with single layer full extent option.</p>


```csharp
public string FullExtentLayerURI { get; set; }
```
### FullExtentOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the option that determines the extent used by the full extent button.</p>


```csharp
public SliderExtentType FullExtentOption { get; set; }
```
### IgnoreInactiveValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to ignore values not currently set to show on the slider.</p>


```csharp
public bool IgnoreInactiveValues { get; set; }
```
### InteractionMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets slider interaction mode.</p>


```csharp
public SliderInteractionMode InteractionMode { get; set; }
```
### IsMinimized

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to collapse the slider over the map view.</p>


```csharp
public bool IsMinimized { get; set; }
```
### LiveMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the slider should continuously progress the slider to the current time.</p>


```csharp
public bool LiveMode { get; set; }
```
### LiveModeOffsetDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the direction to offset the time span relative to the current time.</p>


```csharp
public TimeOffsetDirection LiveModeOffsetDirection { get; set; }
```
### PlayForward

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the play direction is forward.</p>


```csharp
public bool PlayForward { get; set; }
```
### PlayRepeats

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether play continuously repeats until interrupted by user interaction.</p>


```csharp
public bool PlayRepeats { get; set; }
```
### PlayReverses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether play direction will reverse after playing to the end (if repeat is false play will move each direction once then stop).</p>


```csharp
public bool PlayReverses { get; set; }
```
### PlayWaitSeconds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the amount of time to wait between steps.</p>


```csharp
public double PlayWaitSeconds { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SingleTimeSnapUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the time unit to snap to when in 'Single' time snapping mode.</p>


```csharp
public esriTimeUnits SingleTimeSnapUnit { get; set; }
```
### SliderExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the extent shown on the slider.</p>


```csharp
public CIMRange SliderExtent { get; set; }
```
### SliderExtentLocked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the slider extent will not change due to scrolling or using the mouse wheel.</p>


```csharp
public bool SliderExtentLocked { get; set; }
```
### StartValueLocked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the slider's start thumb will not accept mouse events.</p>


```csharp
public bool StartValueLocked { get; set; }
```
### StepCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the number of steps to divide the slider extent into.</p>


```csharp
public double StepCount { get; set; }
```
### StepIntervalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the unit the interval value is in.</p>


```csharp
public esriTimeUnits StepIntervalUnit { get; set; }
```
### StepIntervalValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the specific distance to move the thumbs by when stepping or playing.</p>


```csharp
public double StepIntervalValue { get; set; }
```
### StepLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer to get step information from.</p>


```csharp
public string StepLayerURI { get; set; }
```
### StepOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the chosen method of determining the step size.</p>


```csharp
public SliderStepType StepOption { get; set; }
```
### StepUsesWindow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the step interval value will stay in sync with the sliders value window when possible.</p>


```csharp
public bool StepUsesWindow { get; set; }
```
### TimeSnapMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the option that determines mode used for snapping the map's current time settings.</p>


```csharp
public TimeSnapMode TimeSnapMode { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSliderSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseTimeSnapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether automatic snapping for the map's current time settings is enabled.</p>


```csharp
public bool UseTimeSnapping { get; set; }
```
### UseWindowValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the distance between the start and end thumbs will remain constant.</p>


```csharp
public bool UseWindowValue { get; set; }
```
### WindowUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the unit of the window on the slider.</p>


```csharp
public esriTimeUnits WindowUnit { get; set; }
```
### WindowValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Gets or sets the value of the window on the slider.</p>


```csharp
public double WindowValue { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliderSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


