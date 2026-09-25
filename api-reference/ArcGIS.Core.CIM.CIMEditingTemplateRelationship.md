# CIMEditingTemplateRelationship

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Represents an editing template relationship.</p>


## Object Signature

```csharp
public class CIMEditingTemplateRelationship : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMEditingTemplateRelationship()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Represents an editing template relationship.</p>


```csharp
public CIMEditingTemplateRelationship()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Creates a deep copy of CIMEditingTemplateRelationship.</p>


```csharp
public CIMEditingTemplateRelationship Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Reconstructs the CIMEditingTemplateRelationship with a specified state from a JSON encoding.</p>


```csharp
public static CIMEditingTemplateRelationship FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Gets or sets the relationship ID.</p>


```csharp
public int RelationshipID { get; set; }
```
### TableURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Gets or sets the table URI of the table the relationship corresponds to.</p>


```csharp
public string TableURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMEditingTemplateRelationship and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateRelationship.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


