# CIMFormDatePickerInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Represents a date picker form input.</p>


## Object Signature

```csharp
public class CIMFormDatePickerInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormDatePickerInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Represents a date picker form input.</p>


```csharp
public CIMFormDatePickerInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormDatePickerInput.</p>


```csharp
public CIMFormDatePickerInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormDatePickerInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormDatePickerInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Gets or sets the maximum date to allow. Only the date portion of the timestamp is used.</p>


```csharp
public TimestampOffset Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Gets or sets the minimum date to allow. Only the date portion of the timestamp is used.</p>


```csharp
public TimestampOffset Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormDatePickerInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatePickerInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


