# CIMKGTypeProperty

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type Property.
It is primarily used to configure a property of an entity type or a relationship type within the data model visualization view.</p>


## Object Signature

```csharp
public class CIMKGTypeProperty : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGTypeProperty()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type Property.
It is primarily used to configure a property of an entity type or a relationship type within the data model visualization view.</p>


```csharp
public CIMKGTypeProperty()
```
### AliasName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets the alias name of the property.</p>


```csharp
public string AliasName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGTypeProperty.</p>


```csharp
public CIMKGTypeProperty Clone()
```
### DefaultValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets the default value for the property.</p>


```csharp
public object DefaultValue { get; set; }
```
### DefaultVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the property is visible by default.</p>


```csharp
public bool DefaultVisibility { get; set; }
```
### DomainName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets the domain associated with the property.</p>


```csharp
public string DomainName { get; set; }
```
### Editable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the property is editable.</p>


```csharp
public bool Editable { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Reconstructs the CIMKGTypeProperty with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGTypeProperty FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsNullable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the property can be null.</p>


```csharp
public bool IsNullable { get; set; }
```
### PropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets the name of the property.</p>


```csharp
public string PropertyName { get; set; }
```
### PropertyType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Gets or sets the type of the type property.</p>


```csharp
public esriFieldType PropertyType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGTypeProperty and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeProperty.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


