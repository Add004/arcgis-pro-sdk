# CIMVideoTimelineEventIndicator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Represents an event indicator on a video timeline.</p>


## Object Signature

```csharp
public class CIMVideoTimelineEventIndicator : CIMVideoTimelineIndicator, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVideoTimelineEventIndicator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Represents an event indicator on a video timeline.</p>


```csharp
public CIMVideoTimelineEventIndicator()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVideoTimelineEventIndicator.</p>


```csharp
public CIMVideoTimelineEventIndicator Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Reconstructs the CIMVideoTimelineEventIndicator with a specified state from a JSON encoding.</p>


```csharp
public static CIMVideoTimelineEventIndicator FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Gets or sets the elapsed time from the beginning of the video in ticks for the event.</p>


```csharp
public long Time { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVideoTimelineEventIndicator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineEventIndicator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


