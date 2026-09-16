# CIMKnowledgeGraphDataLoadingEntity

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Entity.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphDataLoadingEntity : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphDataLoadingEntity()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Entity.</p>


```csharp
public CIMKnowledgeGraphDataLoadingEntity()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphDataLoadingEntity.</p>


```csharp
public CIMKnowledgeGraphDataLoadingEntity Clone()
```
### EntityType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets the type of the entity.</p>


```csharp
public string EntityType { get; set; }
```
### EntityTypeExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets the expression which is used to generate the entity type of this entity.
This property takes precedence over the TypeIsFieldName and EntityType properties.
If the EntityTypeExpression property is not null, the EntityType is generated from the script defined in the expression object.
If the EntityTypeExpression property is null, the value of the EntityType property is interpreted based on the TypeIsFieldName property.</p>


```csharp
public CIMExpressionInfo EntityTypeExpression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphDataLoadingEntity with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphDataLoadingEntity FromJson(string json, JsonDeserializationSettings settings = null)
```
### Merge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this entity should be merged.</p>


```csharp
public bool Merge { get; set; }
```
### MultipleTypeLookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this Entity should be found by lookup.
This property takes precedence over EntityType and EntityTypeExpression.
When defined, the entity will be found by searching the specified types and property values.</p>


```csharp
public CIMKnowledgeGraphMultipleTypeLookup MultipleTypeLookup { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets the name of the entity.</p>


```csharp
public string Name { get; set; }
```
### Properties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets the properties of this entity.</p>


```csharp
public CIMKnowledgeGraphProperty[] Properties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphDataLoadingEntity and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeIsFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the Type property
is a name itself or the name of a field.</p>


```csharp
public bool TypeIsFieldName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingEntity.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


