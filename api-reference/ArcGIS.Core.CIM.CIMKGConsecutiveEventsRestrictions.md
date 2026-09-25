# CIMKGConsecutiveEventsRestrictions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Rules defining which &quot;successor&quot; events are allowed to be after a given &quot;predecessor&quot; event.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="3">One implied rule is that a successor event must start at or after the start of the predecessor event.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="5">These rules use the notions of &quot;Gap&quot; and &quot;Overlap&quot; defined hereunder.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="7">Definition of &quot;Overlap&quot;:
When the successor event start is before the predecessor event end,
the overlap is the time from the successor event start to the predecessor event end.
When the successor event start is after the predecessor event end,
the overlap is zero.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="13">Definition of &quot;Gap&quot;:
When the successor event start is before the predecessor event end,
the gap is zero.
When the successor event start is after the predecessor event end,
the gap is the time from the predecessor event end to the successor event start.</p>


## Object Signature

```csharp
public class CIMKGConsecutiveEventsRestrictions : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGConsecutiveEventsRestrictions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Rules defining which &quot;successor&quot; events are allowed to be after a given &quot;predecessor&quot; event.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="3">One implied rule is that a successor event must start at or after the start of the predecessor event.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="5">These rules use the notions of &quot;Gap&quot; and &quot;Overlap&quot; defined hereunder.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="7">Definition of &quot;Overlap&quot;:
When the successor event start is before the predecessor event end,
the overlap is the time from the successor event start to the predecessor event end.
When the successor event start is after the predecessor event end,
the overlap is zero.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="13">Definition of &quot;Gap&quot;:
When the successor event start is before the predecessor event end,
the gap is zero.
When the successor event start is after the predecessor event end,
the gap is the time from the predecessor event end to the successor event start.</p>


```csharp
public CIMKGConsecutiveEventsRestrictions()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGConsecutiveEventsRestrictions.</p>


```csharp
public CIMKGConsecutiveEventsRestrictions Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Reconstructs the CIMKGConsecutiveEventsRestrictions with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGConsecutiveEventsRestrictions FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Gets or sets the max gap.
The unit of this value is MaxGapUnit.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="4">This value is taken into account only if RestrictMaxGap is true.</p>


```csharp
public double MaxGap { get; set; }
```
### MaxGapUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Gets or sets the unit of MaxGap.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="3">Accepted values are {
esriTimeUnitsMilliseconds,
esriTimeUnitsSeconds,
esriTimeUnitsMinutes,
esriTimeUnitsHours,
esriTimeUnitsDays,
esriTimeUnitsWeeks }.</p>


```csharp
public esriTimeUnits MaxGapUnit { get; set; }
```
### MaxOverlap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Gets or sets the max overlap between consecutive events.
The unit of this value is MaxOverlapUnit.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="4">This value is taken into account only if RestrictMaxOverlap is true.</p>


```csharp
public double MaxOverlap { get; set; }
```
### MaxOverlapUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Gets or sets the unit of MaxOverlap.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="3">Accepted values are {
esriTimeUnitsMilliseconds,
esriTimeUnitsSeconds,
esriTimeUnitsMinutes,
esriTimeUnitsHours,
esriTimeUnitsDays,
esriTimeUnitsWeeks }.</p>


```csharp
public esriTimeUnits MaxOverlapUnit { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RestrictMaxGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the max gap is restricted.</p>


```csharp
public bool RestrictMaxGap { get; set; }
```
### RestrictMaxOverlap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the max overlap is restricted.</p>


```csharp
public bool RestrictMaxOverlap { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGConsecutiveEventsRestrictions and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGConsecutiveEventsRestrictions.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


