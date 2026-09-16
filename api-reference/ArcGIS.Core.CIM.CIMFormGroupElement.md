# CIMFormGroupElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Represents a container that holds a set of form elements that can be expanded, collapsed, or displayed
together.</p>


## Object Signature

```csharp
public class CIMFormGroupElement : CIMFormElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormGroupElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Represents a container that holds a set of form elements that can be expanded, collapsed, or displayed
together.</p>


```csharp
public CIMFormGroupElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormGroupElement.</p>


```csharp
public CIMFormGroupElement Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Gets or sets a string that describes the element in detail.</p>


```csharp
public string Description { get; set; }
```
### FormElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Gets or sets an array of CIMFormElement objects that represent an ordered list of form elements.
Nested group elements are not supported.</p>


```csharp
public CIMFormElement[] FormElements { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Reconstructs the CIMFormGroupElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormGroupElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### InitialState

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Gets or sets whether the group should be expanded or collapsed when the form is initially
displayed. If not provided, the default value is Expanded.</p>


```csharp
public FormGroupElementInitialState InitialState { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Gets or sets a string value indicating what the element represents.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormGroupElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisibilityExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is displayed. When the expression evaluates to 'false' the element
is not displayed. If no expression is provided, the default behavior is that the element is
displayed.</p>


```csharp
public string VisibilityExpressionName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormGroupElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


