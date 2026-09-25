# VirtualRelationshipClassDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <b>virtual</b><xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class VirtualRelationshipClassDescription
```


## Members

### VirtualRelationshipClassDescription(Field, Field, RelationshipCardinality)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>VirtualRelationshipClassDescription</code> class.</p>


```csharp
public VirtualRelationshipClassDescription(Field primaryKeyInOriginTable, Field foreignKeyInDestinationTable, RelationshipCardinality cardinality)
```
### BackwardPathLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Gets or sets a backward path label. An optional value.  If not set, the default value is &quot;backward&quot;.</p>


```csharp
public string BackwardPathLabel { get; set; }
```
### Cardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.RelationshipCardinality" data-throw-if-not-resolved="false"></xref> with which the relationship class is created.</p>


```csharp
public RelationshipCardinality Cardinality { get; }
```
### ForeignKeyInDestinationTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> corresponding to the field in the destination table to be used as the foriegn key.</p>


```csharp
public Field ForeignKeyInDestinationTable { get; }
```
### ForwardPathLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Gets or sets a forward path label. An optional value.  If not set, the default value is &quot;forward&quot;.</p>


```csharp
public string ForwardPathLabel { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Gets or sets the name.  An optional value. If not set, a name is generated.</p>


```csharp
public string Name { get; set; }
```
### PrimaryKeyInOriginTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.VirtualRelationshipClassDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> corresponding to the field in the origin table to be used as the primary key.</p>


```csharp
public Field PrimaryKeyInOriginTable { get; }
```


