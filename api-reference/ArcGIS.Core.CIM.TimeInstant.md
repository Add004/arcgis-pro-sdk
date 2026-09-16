# TimeInstant

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Represents an instant in time. The time has no duration.</p>


## Object Signature

```csharp
public class TimeInstant : TimeValue, INotifyPropertyChanged, IXmlSerializable
```


## Members

### TimeInstant()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Represents an instant in time. The time has no duration.</p>


```csharp
public TimeInstant()
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Reconstructs the TimeInstant with a specified state from a JSON encoding.</p>


```csharp
public static TimeInstant FromJson(string json)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Gets or sets the time.</p>


```csharp
public DateTime Time { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Creates a JSON encoding of the TimeInstant and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeInstant.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


