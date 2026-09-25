# CIMFormRadioButtonsInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Represents a radio button group form input.</p>


## Object Signature

```csharp
public class CIMFormRadioButtonsInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormRadioButtonsInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Represents a radio button group form input.</p>


```csharp
public CIMFormRadioButtonsInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormRadioButtonsInput.</p>


```csharp
public CIMFormRadioButtonsInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormRadioButtonsInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormRadioButtonsInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### NoValueOptionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Gets or sets the text used to represent a null value.</p>


```csharp
public string NoValueOptionLabel { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowNoValueOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display a null value option. If not provided, the
default value is 'true'.</p>


```csharp
public bool ShowNoValueOption { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormRadioButtonsInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRadioButtonsInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


