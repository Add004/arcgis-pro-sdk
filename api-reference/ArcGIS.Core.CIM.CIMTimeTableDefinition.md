# CIMTimeTableDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Represents a time table definition.</p>


## Object Signature

```csharp
public class CIMTimeTableDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimeTableDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Represents a time table definition.</p>


```csharp
public CIMTimeTableDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimeTableDefinition.</p>


```csharp
public CIMTimeTableDefinition Clone()
```
### EndTimeField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Gets or sets the end time field.</p>


```csharp
public string EndTimeField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMTimeTableDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimeTableDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartTimeField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Gets or sets the start time field.</p>


```csharp
public string StartTimeField { get; set; }
```
### TimeValueFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Gets or sets the time value format.</p>


```csharp
public string TimeValueFormat { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimeTableDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrackIDField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Gets or sets the track ID field.</p>


```csharp
public string TrackIDField { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeTableDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


