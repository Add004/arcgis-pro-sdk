# CIMFormTextBoxInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Represents a single-line text box form input.</p>


## Object Signature

```csharp
public class CIMFormTextBoxInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormTextBoxInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Represents a single-line text box form input.</p>


```csharp
public CIMFormTextBoxInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormTextBoxInput.</p>


```csharp
public CIMFormTextBoxInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormTextBoxInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormTextBoxInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Gets or sets the maximum number of characters allowed. This only applies for string fields.
If set (or defaulted) to -1, the value is derived from the length property of the referenced
field in the service.</p>


```csharp
public long MaxLength { get; set; }
```
### MinLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Gets or sets the minimum number of characters allowed. This only applies for string fields.
If set (or defaulted) to 0, there is no minimum constraint.</p>


```csharp
public long MinLength { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormTextBoxInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextBoxInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


