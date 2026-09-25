# AttributedRelationshipClassDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AttributedRelationshipClassDescription : RelationshipClassDescription
```


## Members

### AttributedRelationshipClassDescription(AttributedRelationshipClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributedRelationshipClassDescription(AttributedRelationshipClassDefinition attributedRelationshipClassDefinition)
```
### AttributedRelationshipClassDescription(AttributedRelationshipClassToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributedRelationshipClassDescription(AttributedRelationshipClassToken attributedRelationshipClassToken)
```
### AttributedRelationshipClassDescription(string, AttributedRelationshipClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributedRelationshipClassDescription(string attributedRelationshipClassName, AttributedRelationshipClassDefinition attributedRelationshipClassDefinition)
```
### AttributedRelationshipClassDescription(string, TableDescription, TableDescription, RelationshipCardinality, string, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributedRelationshipClassDescription(string attributedRelationshipClassName, TableDescription originClassDescription, TableDescription destinationClassDescription, RelationshipCardinality relationshipCardinality, string originPrimaryKey, string originForeignKey, string destinationPrimaryKey, string destinationForeignKey)
```
### DestinationForeignKeyFieldDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">The destination foreign key field in the intermediate relationship class table.</p>


```csharp
public FieldDescription DestinationForeignKeyFieldDescription { get; }
```
### DestinationPrimaryKeyFieldDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">The destination primary key field in the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription.DestinationClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldDescription DestinationPrimaryKeyFieldDescription { get; }
```
### FieldDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription.yml" sourcestartlinenumber="1">The fields to add to the intermediate relationship class table.</p>


```csharp
public List<FieldDescription> FieldDescriptions { get; }
```


