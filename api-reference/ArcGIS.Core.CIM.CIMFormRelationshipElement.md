# CIMFormRelationshipElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Represents how a relationship between feature layers and tables can participate in the form. When
present in the form, the user may have the option to add or edit related records.</p>


## Object Signature

```csharp
public class CIMFormRelationshipElement : CIMFormElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormRelationshipElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Represents how a relationship between feature layers and tables can participate in the form. When
present in the form, the user may have the option to add or edit related records.</p>


```csharp
public CIMFormRelationshipElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormRelationshipElement.</p>


```csharp
public CIMFormRelationshipElement Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets a string that describes the element in detail.</p>


```csharp
public string Description { get; set; }
```
### DisplayCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets an integer that indicates the maximum number of records to display. If set (or
defaulted) to -1, there is no maximum.</p>


```csharp
public long DisplayCount { get; set; }
```
### DisplayType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets how related records should be displayed.</p>


```csharp
public FormRelationshipDisplayType DisplayType { get; set; }
```
### EditableExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is editable. When the expression evaluates to 'false' the element
is not editable. If the referenced related table is not editable, the editable expression is
ignored and the element is not editable.</p>


```csharp
public string EditableExpressionName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Reconstructs the CIMFormRelationshipElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormRelationshipElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets a string value indicating what the element represents.</p>


```csharp
public string Label { get; set; }
```
### OrderByFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets the array of orderByField objects indicating the display order for the related
records, and whether they should be sorted in ascending or descending order.</p>


```csharp
public CIMFeatureSortInfo[] OrderByFields { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets the name of the relationship as defined in the feature layer definition.</p>


```csharp
public string RelationshipName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormRelationshipElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisibilityExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is displayed. When the expression evaluates to 'false' the element
is not displayed. If no expression is provided, the default behavior is that the element is
displayed.</p>


```csharp
public string VisibilityExpressionName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormRelationshipElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


