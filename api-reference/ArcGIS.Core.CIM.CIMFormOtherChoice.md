# CIMFormOtherChoice

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Represents an 'Other' choice for multiple choice input, capturing free text from the user
when none of the predefined choices are appropriate.</p>


## Object Signature

```csharp
public class CIMFormOtherChoice : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormOtherChoice()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Represents an 'Other' choice for multiple choice input, capturing free text from the user
when none of the predefined choices are appropriate.</p>


```csharp
public CIMFormOtherChoice()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormOtherChoice.</p>


```csharp
public CIMFormOtherChoice Clone()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Gets or sets the name of the field in which to store the value entered when the 'Other' choice is selected.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Reconstructs the CIMFormOtherChoice with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormOtherChoice FromJson(string json, JsonDeserializationSettings settings = null)
```
### Hint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Gets or sets placeholder text when the 'Other' choice is selected. If not provided, no hint text will be
displayed.</p>


```csharp
public string Hint { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Gets or sets the text to use for the 'Other' choice label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormOtherChoice and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormOtherChoice.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


