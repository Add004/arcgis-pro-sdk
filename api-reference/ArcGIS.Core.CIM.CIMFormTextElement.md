# CIMFormTextElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Represents a form element containing read-only text.</p>


## Object Signature

```csharp
public class CIMFormTextElement : CIMFormElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormTextElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Represents a form element containing read-only text.</p>


```csharp
public CIMFormTextElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormTextElement.</p>


```csharp
public CIMFormTextElement Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Reconstructs the CIMFormTextElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormTextElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Gets or sets the string value indicating the text to be displayed within the formTextElement.</p>


```csharp
public string Text { get; set; }
```
### TextFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Gets or sets the format of the 'text' property. Default is PlainText.</p>


```csharp
public FormTextElementFormat TextFormat { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormTextElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisibilityExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is displayed. When the expression evaluates to 'false' the element
is not displayed. If no expression is provided, the default behavior is that the element is
displayed.</p>


```csharp
public string VisibilityExpressionName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormTextElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


