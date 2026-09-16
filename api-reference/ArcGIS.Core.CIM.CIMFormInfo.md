# CIMFormInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Represents the form configuration for when a user edits a feature.</p>


## Object Signature

```csharp
public class CIMFormInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Represents the form configuration for when a user edits a feature.</p>


```csharp
public CIMFormInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormInfo.</p>


```csharp
public CIMFormInfo Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Gets or sets a string that appears in the body of the form as a description.</p>


```csharp
public string Description { get; set; }
```
### ExpressionInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Gets or sets the list of Arcade expressions used in the form.</p>


```csharp
public CIMExpressionInfo[] ExpressionInfos { get; set; }
```
### FormElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Gets or sets an array of formElement objects that represent an ordered list of form elements.</p>


```csharp
public CIMFormElement[] FormElements { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMFormInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### PreserveFieldValuesWhenHidden

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a previously visible 'formFieldElement' value is retained
or cleared when a 'visibilityExpression' applied on the 'formFieldElement' or its parent
'formGroupElement' evaluates to 'false'. Default is 'false'.</p>


```csharp
public bool PreserveFieldValuesWhenHidden { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Gets or sets a string that appears at the top of the form as a title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


