# CIMKnowledgeGraphDataLoadingRelationship

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Relationship.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphDataLoadingRelationship : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphDataLoadingRelationship()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Relationship.</p>


```csharp
public CIMKnowledgeGraphDataLoadingRelationship()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphDataLoadingRelationship.</p>


```csharp
public CIMKnowledgeGraphDataLoadingRelationship Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphDataLoadingRelationship with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphDataLoadingRelationship FromJson(string json, JsonDeserializationSettings settings = null)
```
### Merge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this relationship should be merged.</p>


```csharp
public bool Merge { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets the name of the relationship.</p>


```csharp
public string Name { get; set; }
```
### Properties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets the properties of this relationship.</p>


```csharp
public CIMKnowledgeGraphProperty[] Properties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets the type of the relationship.</p>


```csharp
public string RelationshipType { get; set; }
```
### RelationshipTypeExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets the expression which is used to generate the relationship type of this relationship.
This property takes precedence over the TypeIsFieldName and RelationshipType properties.
If the RelationshipTypeExpression is not null, the RelationshipType is generated from the script defined in the expression object.
If the RelationshipTypeExpression is null, the value of the RelationshipType property is interpreted based on the TypeIsFieldName property.</p>


```csharp
public CIMExpressionInfo RelationshipTypeExpression { get; set; }
```
### SourceEntityName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets the source entity name.</p>


```csharp
public string SourceEntityName { get; set; }
```
### TargetEntityName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets the target entity name.</p>


```csharp
public string TargetEntityName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphDataLoadingRelationship and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeIsFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the Type property
is a name itself or the name of a field.</p>


```csharp
public bool TypeIsFieldName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingRelationship.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


