# CIMFormComboBoxInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Represents a form input consisting of a list of values in a drop-down that supports typing to
filter. Only one value can be selected at a time.</p>


## Object Signature

```csharp
public class CIMFormComboBoxInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormComboBoxInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Represents a form input consisting of a list of values in a drop-down that supports typing to
filter. Only one value can be selected at a time.</p>


```csharp
public CIMFormComboBoxInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormComboBoxInput.</p>


```csharp
public CIMFormComboBoxInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormComboBoxInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormComboBoxInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### NoValueOptionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Gets or sets the text used to represent a null value.</p>


```csharp
public string NoValueOptionLabel { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowNoValueOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display a null value option. If not provided, the
default value is 'true'.</p>


```csharp
public bool ShowNoValueOption { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormComboBoxInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormComboBoxInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


