# CIMKGTimeFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">A Knowledge Graph Time Filter represents a set of time constraints that apply to the &quot;events&quot; of a path.</p>


## Object Signature

```csharp
public class CIMKGTimeFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">&quot;Events&quot; are entities and relationships of the path that have a matching <xref href="ArcGIS.Core.CIM.CIMKGEventDefinition" data-throw-if-not-resolved="false"></xref> in <xref href="ArcGIS.Core.CIM.CIMKGTimeFilter.EventsDefinitions" data-throw-if-not-resolved="false"></xref>.<br><br>
A CIMKGEventDefinition can either be durative (one property represents the start time, and one property representing the end time)
or &quot;punctual&quot; (a single property represents the time at which the event occurs).<br><br>
The time filter represents three kinds of time constraints:<br></p>
<ul sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="5">
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="5">constraints that are applied to all events of the path (<xref href="ArcGIS.Core.CIM.CIMKGTimeFilter.TimeWindow" data-throw-if-not-resolved="false"></xref>),<br></li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="6">constraints that are applied only to durative events of the path (<xref href="ArcGIS.Core.CIM.CIMKGTimeFilter.DurativeEventsDurationConstraint" data-throw-if-not-resolved="false"></xref>).<br></li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="7">constraints that are applied to all pairs of consecutive events of the path (<xref href="ArcGIS.Core.CIM.CIMKGTimeFilter.KGPathTimeFlow" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.CIM.CIMKGTimeFilter.ConsecutiveEventsRestrictions" data-throw-if-not-resolved="false"></xref>).<br><br>
The time filter also specifies the behavior when an event has missing or ill-formed time information (<xref href="ArcGIS.Core.CIM.CIMKGTimeFilter.EventErrorHandling" data-throw-if-not-resolved="false"></xref>).</li>
</ul>


## Members

### CIMKGTimeFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">A Knowledge Graph Time Filter represents a set of time constraints that apply to the &quot;events&quot; of a path.</p>


```csharp
public CIMKGTimeFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGTimeFilter.</p>


```csharp
public CIMKGTimeFilter Clone()
```
### ConsecutiveEventsRestrictions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets the consecutive events restrictions.</p>


```csharp
public CIMKGConsecutiveEventsRestrictions ConsecutiveEventsRestrictions { get; set; }
```
### DurativeEventsDurationConstraint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets the constraint on durative events duration.</p>


```csharp
public CIMKGDurativeEventsDurationConstraint DurativeEventsDurationConstraint { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the filter is enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### EventErrorHandling

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets a value indicating how event data errors should be handled.</p>


```csharp
public CIMKGEventErrorHandling EventErrorHandling { get; set; }
```
### EventsDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets the events definitions.</p>


```csharp
public CIMKGEventsDefinitions EventsDefinitions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMKGTimeFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGTimeFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### KGPathTimeFlow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets a value indicating how time should flow along the result paths.</p>


```csharp
public KGPathTimeFlow KGPathTimeFlow { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeWindow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Gets or sets the time window. Any event that has a time span not intersecting the time window will be excluded.</p>


```csharp
public CIMKGTimeWindow TimeWindow { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGTimeFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTimeFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


