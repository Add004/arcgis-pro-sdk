# KnowledgeGraphEntityTypeDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription" data-throw-if-not-resolved="false"></xref>. See
also <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphRelationshipTypeDescription" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphEntityTypeDescription : KnowledgeGraphTypeDescription
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">There are a number of different constructor overloads provided allowing an entity type
description to be initialized from a number of different sources including:
<br>A table or feature class definition.
<br>A <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType" data-throw-if-not-resolved="false"></xref>.
<br>Another KnowledgeGraphRelationshipTypeDescription.
<br>A collection of <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription" data-throw-if-not-resolved="false"></xref>.
<br>Various other overloads that also include a name and spatial column (&quot;shape description&quot;).
<br>Note: A spatial column for both KnowledgeGraphEntityTypes and KnowledgeGraphRelationshipTypes is
optional. KnowledgeGraphEntityTypes and KnowledgeGraphRelationshipTypes created with a
shape column will be represented as feature classes in the knowledge graph geodatabase and
KnowledgeGraphEntityTypes and KnowledgeGraphRelationshipTypes created without a shape column will
be represented as tables.<br>
When initializing a KnowledgeGraphEntityTypeDescription, an ObjectID and GlobalID KnowledgeGraphPropertyDescription
will automatically be added to the list of property descriptions (if they were not provided as
inputs to the relevant constructor) within the <xref href="ArcGIS.Core.Data.DDL.SchemaBuilder" data-throw-if-not-resolved="false"></xref>. In the case
of the relationship type, the underlying origin and destination entity id fields will also be automatically be
added to the list of property descriptions within the <xref href="ArcGIS.Core.Data.DDL.SchemaBuilder" data-throw-if-not-resolved="false"></xref></p>


## Members

### KnowledgeGraphEntityTypeDescription(KnowledgeGraphEntityType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(KnowledgeGraphEntityType entityType)
```
### KnowledgeGraphEntityTypeDescription(TableDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given
<xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref>. This method must be
called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(TableDefinition tableDefinition)
```
### KnowledgeGraphEntityTypeDescription(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name)
```
### KnowledgeGraphEntityTypeDescription(string, ShapeDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name and shape
description. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, ShapeDescription shapeDescription)
```
### KnowledgeGraphEntityTypeDescription(string, KnowledgeGraphEntityType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name and
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, KnowledgeGraphEntityType entityType)
```
### KnowledgeGraphEntityTypeDescription(string, KnowledgeGraphEntityType, ShapeDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name,
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType" data-throw-if-not-resolved="false"></xref> and shape definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, KnowledgeGraphEntityType entityType, ShapeDescription shapeDescription)
```
### KnowledgeGraphEntityTypeDescription(string, TableDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name and
<xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref>. This method must be called
on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, TableDefinition tableDefinition)
```
### KnowledgeGraphEntityTypeDescription(string, TableDefinition, ShapeDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name,
<xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref>, and shape description.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, TableDefinition tableDefinition, ShapeDescription shapeDescription)
```
### KnowledgeGraphEntityTypeDescription(string, IEnumerable&lt;KnowledgeGraphPropertyDescription&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name and collection
of property descriptions. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, IEnumerable<KnowledgeGraphPropertyDescription> propertyDescriptions)
```
### KnowledgeGraphEntityTypeDescription(string, IEnumerable&lt;KnowledgeGraphPropertyDescription&gt;, ShapeDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription.yml" sourcestartlinenumber="1">Construct a KnowledgeGraphEntityTypeDescription with the given name, collection
of property descriptions, and shape description. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityTypeDescription(string name, IEnumerable<KnowledgeGraphPropertyDescription> propertyDescriptions, ShapeDescription shapeDescription)
```


