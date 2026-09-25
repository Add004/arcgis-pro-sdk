# TimeExtent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Represents an extent of time defined by a start and end date.</p>


## Object Signature

```csharp
public class TimeExtent : TimeValue, INotifyPropertyChanged, IXmlSerializable
```


## Members

### TimeExtent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Default constructor for TimeExtent</p>


```csharp
public TimeExtent()
```
### Empty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the time extent is empty.</p>


```csharp
public bool Empty { get; set; }
```
### EndTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Gets or sets the end time of the extent.</p>


```csharp
public DateTime EndTime { get; set; }
```
### EndTimeSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the extent contains an end time. If false the time extent has no upper bound.</p>


```csharp
public bool EndTimeSpecified { get; set; }
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Reconstructs the TimeExtent with a specified state from a JSON encoding.</p>


```csharp
public static TimeExtent FromJson(string json)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Gets or sets the start time of the extent.</p>


```csharp
public DateTime StartTime { get; set; }
```
### StartTimeSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the extent contains a start time. If false the time extent has no lower bound.</p>


```csharp
public bool StartTimeSpecified { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Creates a JSON encoding of the TimeExtent and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeExtent.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


