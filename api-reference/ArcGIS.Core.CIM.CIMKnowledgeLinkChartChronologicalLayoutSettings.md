# CIMKnowledgeLinkChartChronologicalLayoutSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Contains settings to be used in chronological layout calculations.</p>


## Object Signature

```csharp
public class CIMKnowledgeLinkChartChronologicalLayoutSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeLinkChartChronologicalLayoutSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Contains settings to be used in chronological layout calculations.</p>


```csharp
public CIMKnowledgeLinkChartChronologicalLayoutSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeLinkChartChronologicalLayoutSettings.</p>


```csharp
public CIMKnowledgeLinkChartChronologicalLayoutSettings Clone()
```
### DurationLineWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating the width of the line, in points, representing the duration of an event with non-zero duration.</p>


```csharp
public int DurationLineWidth { get; set; }
```
### EntityPositionAtDurationRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating where the entity of a non-zero duration event will be placed.
0.0 represents the start of the duration interval, 1.0 represents the end of the duration interval.
Used in multi-timeline layout only.</p>


```csharp
public double EntityPositionAtDurationRatio { get; set; }
```
### EventsTicksVisualization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the event ticks visualization option.
Event ticks are displayed in the time banner.</p>


```csharp
public EventsTicksVisualization EventsTicksVisualization { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeLinkChartChronologicalLayoutSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeLinkChartChronologicalLayoutSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineSeparationMultiplier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the multiplier used for line separation.
Lines will be more separated with a higher multiplier.</p>


```csharp
public double LineSeparationMultiplier { get; set; }
```
### MoveFirstBends

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the first bend on a relationship line related to an event
is moved higher up from the event location when some events are separated.
Used only in the mono-timeline layout, when 'SeparateTimelineOverlaps' is true.</p>


```csharp
public bool MoveFirstBends { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SecondBendRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the ratio at which the second bend or a relationship occurs, for event relationships
and non-event relationships between events and non-event entities.
Used only in the mono-timeline layout.</p>


```csharp
public double SecondBendRatio { get; set; }
```
### SeparateTimeOverlaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether events that overlap in time are separated.</p>


```csharp
public bool SeparateTimeOverlaps { get; set; }
```
### SeparateTimelineOverlaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether events that overlap on a timeline are separated.</p>


```csharp
public bool SeparateTimelineOverlaps { get; set; }
```
### SeparatedLineShapeRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the separated line shape ratio.
When the ratio is high, the angle between the extremities of the separated line geometry
and the original line is small.</p>


```csharp
public double SeparatedLineShapeRatio { get; set; }
```
### ShowDurationLineForNonZeroDurationEntityEvents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether lines representing the duration of events with non-zero durations are shown.</p>


```csharp
public bool ShowDurationLineForNonZeroDurationEntityEvents { get; set; }
```
### ShowNonZeroDurationIntervalBounds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether duration interval bounds are represented in relationship lines of events that have non-zero durations.
Used in multi-timeline layout only.</p>


```csharp
public bool ShowNonZeroDurationIntervalBounds { get; set; }
```
### SpaceSeparatedLinesEvenly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether separated lines are spaced evenly.
When true, the offset for the i-th overlapping line is proportional to 'i'.
When false, the offset for the i-th overlapping line is proportional to 'squareRoot(i)'.</p>


```csharp
public bool SpaceSeparatedLinesEvenly { get; set; }
```
### TimeBannerUTCOffsetInMinutes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the UTC offset of the time banner, in minutes.</p>


```csharp
public int TimeBannerUTCOffsetInMinutes { get; set; }
```
### TimeDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the time axis direction.</p>


```csharp
public LinkChartLayoutDirection TimeDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeLinkChartChronologicalLayoutSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseBezierCurves

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use Bezier curves to represent separated lines.</p>


```csharp
public bool UseBezierCurves { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartChronologicalLayoutSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


