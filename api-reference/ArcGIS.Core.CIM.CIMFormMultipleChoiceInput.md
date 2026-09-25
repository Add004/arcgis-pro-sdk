# CIMFormMultipleChoiceInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Represents a checkbox group where multiple choices can be selected. Applies to string fields only.</p>


## Object Signature

```csharp
public class CIMFormMultipleChoiceInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormMultipleChoiceInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Represents a checkbox group where multiple choices can be selected. Applies to string fields only.</p>


```csharp
public CIMFormMultipleChoiceInput()
```
### ChoiceDelimiter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Gets or sets the delimiter used to join multiple selected choice values. If not provided, a comma (,)
will be used as the default delimiter. Choice values cannot contain the delimiter character. The delimiter
must be a single character (a string of length 1).</p>


```csharp
public string ChoiceDelimiter { get; set; }
```
### Choices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Gets or sets the choices presented in the checkbox group. Choices are presented in the order they
appear within this array.</p>


```csharp
public CIMFormChoice[] Choices { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormMultipleChoiceInput.</p>


```csharp
public CIMFormMultipleChoiceInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormMultipleChoiceInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormMultipleChoiceInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludeSelectAllChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to include an option to select/unselect all choices. If not
defined, only defined choices (and the 'other' choice) are displayed.</p>


```csharp
public bool IncludeSelectAllChoices { get; set; }
```
### MaximumChoiceCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Gets or sets the maximum number of choices that may be selected. If set (or defaulted) to -1, there is
no maximum.</p>


```csharp
public int MaximumChoiceCount { get; set; }
```
### MinimumChoiceCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Gets or sets the minimum number of choices that must be selected. If this property is set (or defaulted)
to zero and the associated field is non-nullable, then at least one choice must be selected. If the property
is set (or defaulted) to zero and the field is nullable, selecting no choices is acceptable.</p>


```csharp
public int MinimumChoiceCount { get; set; }
```
### OtherChoice

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Gets or sets the properties for the 'Other' choice.</p>


```csharp
public CIMFormOtherChoice OtherChoice { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormMultipleChoiceInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormMultipleChoiceInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


