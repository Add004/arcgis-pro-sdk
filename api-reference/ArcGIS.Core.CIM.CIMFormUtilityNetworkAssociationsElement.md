# CIMFormUtilityNetworkAssociationsElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Represents how a utility network associations element can participate in the form. When present in the
form, the user may have the option to view related utility network associations.</p>


## Object Signature

```csharp
public class CIMFormUtilityNetworkAssociationsElement : CIMFormElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormUtilityNetworkAssociationsElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Represents how a utility network associations element can participate in the form. When present in the
form, the user may have the option to view related utility network associations.</p>


```csharp
public CIMFormUtilityNetworkAssociationsElement()
```
### AssociationTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Gets or sets the array of objects that define the type of associations to display in the pop-up.</p>


```csharp
public CIMPopupUtilityNetworkAssociation[] AssociationTypes { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormUtilityNetworkAssociationsElement.</p>


```csharp
public CIMFormUtilityNetworkAssociationsElement Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Gets or sets a string that describes the element in detail.</p>


```csharp
public string Description { get; set; }
```
### EditableExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is editable. When the expression evaluates to 'false' the element
is not editable. If the referenced related table is not editable, the editable expression is
ignored and the element is not editable.</p>


```csharp
public string EditableExpressionName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Reconstructs the CIMFormUtilityNetworkAssociationsElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormUtilityNetworkAssociationsElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Gets or sets a string value indicating what the element represents.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormUtilityNetworkAssociationsElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisibilityExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is displayed. When the expression evaluates to 'false' the element
is not displayed. If no expression is provided, the default behavior is that the element is
displayed.</p>


```csharp
public string VisibilityExpressionName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormUtilityNetworkAssociationsElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


