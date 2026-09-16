# CIMVideoTimelineRangeIndicator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Represents a range indicator on a video timeline.</p>


## Object Signature

```csharp
public class CIMVideoTimelineRangeIndicator : CIMVideoTimelineIndicator, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVideoTimelineRangeIndicator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Represents a range indicator on a video timeline.</p>


```csharp
public CIMVideoTimelineRangeIndicator()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVideoTimelineRangeIndicator.</p>


```csharp
public CIMVideoTimelineRangeIndicator Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Reconstructs the CIMVideoTimelineRangeIndicator with a specified state from a JSON encoding.</p>


```csharp
public static CIMVideoTimelineRangeIndicator FromJson(string json, JsonDeserializationSettings settings = null)
```
### Maximum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Gets or sets the elapsed time from the beginning of the video in ticks for the maximum time in the range.</p>


```csharp
public long Maximum { get; set; }
```
### Minimum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Gets or sets the elapsed time from the beginning of the video in ticks for the minimum time in the range.</p>


```csharp
public long Minimum { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVideoTimelineRangeIndicator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineRangeIndicator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


