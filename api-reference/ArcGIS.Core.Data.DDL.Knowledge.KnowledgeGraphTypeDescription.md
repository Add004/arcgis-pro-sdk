# KnowledgeGraphTypeDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription.yml" sourcestartlinenumber="1">Abstract base class for <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphEntityTypeDescription" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphRelationshipTypeDescription" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class KnowledgeGraphTypeDescription : Description
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription.yml" sourcestartlinenumber="1">Entity and relationship types both derive from the base named object type <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType" data-throw-if-not-resolved="false"></xref>.
The presence of a spatial column for either of Entity and Relationship types (within a knowledge graph) is optional. All geometries
within a knowledge graph must share the same spatial reference <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetSpatialReference" data-throw-if-not-resolved="false"></xref></p>


## Members

### AliasName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription.yml" sourcestartlinenumber="1">The alias name of the named type.</p>


```csharp
public string AliasName { get; set; }
```
### HasShapeDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription.yml" sourcestartlinenumber="1">Gets whether the description has a spatial description property or not.</p>


```csharp
public bool HasShapeDescription { get; }
```
### PropertyDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription.yml" sourcestartlinenumber="1">Gets the collection of property descriptions for the knowledge graph type description</p>


```csharp
public IReadOnlyList<KnowledgeGraphPropertyDescription> PropertyDescriptions { get; }
```
### ShapeDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription.yml" sourcestartlinenumber="1">Represents the shape <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ShapeDescription ShapeDescription { get; }
```


