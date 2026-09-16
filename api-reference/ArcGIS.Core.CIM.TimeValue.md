# TimeValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Represents the base class for <xref href="ArcGIS.Core.CIM.TimeExtent" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.CIM.TimeInstant" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TimeValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### TimeValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Represents the base class for <xref href="ArcGIS.Core.CIM.TimeExtent" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.CIM.TimeInstant" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TimeValue()
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Reconstructs the TimeInstant with a specified state from a JSON encoding.</p>


```csharp
public static TimeInstant FromJson(string json)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Gets or sets the time zone definition of the time.</p>


```csharp
public TimeReference TimeReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the TimeReference and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpdateTimeZone(DateTime)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">This method is obsolete.</p>


```csharp
[Obsolete]
protected DateTime UpdateTimeZone(DateTime dateTime)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.TimeValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


