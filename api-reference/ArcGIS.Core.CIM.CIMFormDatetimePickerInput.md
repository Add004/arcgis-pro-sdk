# CIMFormDatetimePickerInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Represents a calendar date picker form input.</p>


## Object Signature

```csharp
public class CIMFormDatetimePickerInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormDatetimePickerInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Represents a calendar date picker form input.</p>


```csharp
public CIMFormDatetimePickerInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormDatetimePickerInput.</p>


```csharp
public CIMFormDatetimePickerInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormDatetimePickerInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormDatetimePickerInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludeTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the datetime picker should provide an option to select the
time. If not provided, the default value is 'false'.</p>


```csharp
public bool IncludeTime { get; set; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Gets or sets the maximum date to allow. The offset of the timestamp is ignored.</p>


```csharp
public TimestampOffset Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Gets or sets the minimum date to allow. The offset of the timestamp is ignored.</p>


```csharp
public TimestampOffset Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormDatetimePickerInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDatetimePickerInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


