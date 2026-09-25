# CIMFormTimestampOffsetPickerInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Represents a calendar date and time picker form input, with timezone offset.</p>


## Object Signature

```csharp
public class CIMFormTimestampOffsetPickerInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormTimestampOffsetPickerInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Represents a calendar date and time picker form input, with timezone offset.</p>


```csharp
public CIMFormTimestampOffsetPickerInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormTimestampOffsetPickerInput.</p>


```csharp
public CIMFormTimestampOffsetPickerInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormTimestampOffsetPickerInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormTimestampOffsetPickerInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludeTimeOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the timestampoffset picker should provide an option to
select the timeoffset. If not provided, the default value is 'true'.</p>


```csharp
public bool IncludeTimeOffset { get; set; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Gets or sets the maximum timestampoffset to allow.</p>


```csharp
public TimestampOffset Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Gets or sets the minimum timestampoffset to allow.</p>


```csharp
public TimestampOffset Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Gets or sets the resolution identifier. The default value is Minutes.</p>


```csharp
public FormTimeInputResolution TimeResolution { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormTimestampOffsetPickerInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTimestampOffsetPickerInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


