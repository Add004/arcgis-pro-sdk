# TimestampOffset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Represents a timestamp plus an offset in hours and/or minutes.</p>


## Object Signature

```csharp
public class TimestampOffset : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### TimestampOffset()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Represents a timestamp plus an offset in hours and/or minutes.</p>


```csharp
public TimestampOffset()
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Reconstructs the TimestampOffset with a specified state from a JSON encoding.</p>


```csharp
public static TimestampOffset FromJson(string json)
```
### HoursOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Gets or set the offset in hours.</p>


```csharp
public short HoursOffset { get; set; }
```
### MinutesOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Gets or sets the offset in minutes.</p>


```csharp
public short MinutesOffset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Timestamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Gets or sets the timestamp.</p>


```csharp
public DateTime Timestamp { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Creates a JSON encoding of the TimestampOffset and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimestampOffset.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


