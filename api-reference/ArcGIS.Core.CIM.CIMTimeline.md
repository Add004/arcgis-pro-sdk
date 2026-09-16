# CIMTimeline

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Represents a timeline.</p>


## Object Signature

```csharp
public class CIMTimeline : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimeline()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Represents a timeline.</p>


```csharp
public CIMTimeline()
```
### BinningTimespan

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the time units used in summary view bin time.</p>


```csharp
public esriTimeUnits BinningTimespan { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimeline.</p>


```csharp
public CIMTimeline Clone()
```
### EndTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the time at the end of the timeline.</p>


```csharp
public TimeInstant EndTime { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the timeline is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Reconstructs the CIMTimeline with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimeline FromJson(string json, JsonDeserializationSettings settings = null)
```
### HonorExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the items in the timeline are visible based on the map extent.</p>


```csharp
public bool HonorExtent { get; set; }
```
### HonorRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the items in the timeline are visible based on range.</p>


```csharp
public bool HonorRange { get; set; }
```
### HonorSelection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the items in the timeline are visible based on the map selection.</p>


```csharp
public bool HonorSelection { get; set; }
```
### HonorTimeSlider

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the timeline syncs with the map time slider.</p>


```csharp
public bool HonorTimeSlider { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the selection set.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### ShowSwimlaneLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the timeline swimlanes show labels.</p>


```csharp
public bool ShowSwimlaneLabels { get; set; }
```
### ShowSwimlanes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the timeline shows swimlanes.</p>


```csharp
public bool ShowSwimlanes { get; set; }
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the time at the beginning of the timeline.</p>


```csharp
public TimeInstant StartTime { get; set; }
```
### Swimlanes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the timeline swimlanes.</p>


```csharp
public CIMTimelineSwimlane[] Swimlanes { get; set; }
```
### Theme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the theme of the timeline. e.g. Light, Medium, or Dark.</p>


```csharp
public TimelineTheme Theme { get; set; }
```
### TimeIndicator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the time indicator. e.g. Small, Medium, or Large.</p>


```csharp
public TimeIndicatorSize TimeIndicator { get; set; }
```
### TimelineTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the timeline.</p>


```csharp
public CIMTextSymbol TimelineTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimeline and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Units

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets time units used in the timeline scale.</p>


```csharp
public esriTimeUnits Units { get; set; }
```
### ViewType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Gets or sets the timeline view type.</p>


```csharp
public TimelineViewType ViewType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeline.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


