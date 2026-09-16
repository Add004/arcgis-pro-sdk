# RelationshipClassDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class RelationshipClassDescription : Description
```


## Members

### RelationshipClassDescription(RelationshipClassToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RelationshipClassDescription(RelationshipClassToken relationshipClassToken)
```
### RelationshipClassDescription(RelationshipClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RelationshipClassDescription(RelationshipClassDefinition relationshipClassDefinition)
```
### RelationshipClassDescription(string, TableDescription, TableDescription, RelationshipCardinality, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RelationshipClassDescription(string relationshipClassName, TableDescription originClassDescription, TableDescription destinationClassDescription, RelationshipCardinality relationshipCardinality, string originPrimaryKey, string originForeignKey)
```
### RelationshipClassDescription(string, RelationshipClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RelationshipClassDescription(string relationshipClassName, RelationshipClassDefinition relationshipClassDefinition)
```
### BackwardPathLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the backward path label of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> to uniquely identify the relationship when navigating from the destination to the origin.</p>


```csharp
public string BackwardPathLabel { get; init; }
```
### DestinationClassDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the destination class of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableDescription DestinationClassDescription { get; }
```
### ForwardPathLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the forward path label of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> to uniquely identify the relationship when navigating from the origin to the destination.</p>


```csharp
public string ForwardPathLabel { get; init; }
```
### OriginClassDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the origin class of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableDescription OriginClassDescription { get; }
```
### OriginForeignKeyFieldDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the origin foreign key field in the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription.DestinationClassDescription" data-throw-if-not-resolved="false"></xref>
for a <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> or the origin foreign key field in the intermediate table
for an <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldDescription OriginForeignKeyFieldDescription { get; }
```
### OriginPrimaryKeyFieldDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the origin primary key field in the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription.OriginClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldDescription OriginPrimaryKeyFieldDescription { get; }
```
### RelationshipCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the relationship cardinality.</p>


```csharp
public RelationshipCardinality RelationshipCardinality { get; }
```
### RelationshipMessageDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the message notification direction between origin and destination class.</p>


```csharp
public RelationshipMessageDirection RelationshipMessageDirection { get; init; }
```
### RelationshipRuleDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the relationship rule descriptions.</p>


```csharp
public List<RelationshipRuleDescription> RelationshipRuleDescriptions { get; }
```
### RelationshipSplitPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets and sets the relationship split policy.</p>


```csharp
public RelationshipSplitPolicy RelationshipSplitPolicy { get; set; }
```
### RelationshipType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the relationship type.</p>


```csharp
public RelationshipType RelationshipType { get; init; }
```


