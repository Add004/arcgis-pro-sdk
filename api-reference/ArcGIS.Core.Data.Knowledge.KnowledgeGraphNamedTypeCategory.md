# KnowledgeGraphNamedTypeCategory

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Represents the category of a named type.
The default is unspecified. Other options include entity,
relationship, both entity and relationship, and provenance.
Currently used to communicate search targets.</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="8">The categories supported by the Knowledge Graph is determined by
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.GetSupportedSearchTargets" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum KnowledgeGraphNamedTypeCategory
```


## Members

### BothEntityRelationship

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Both entity and relationship.</p>


```csharp
BothEntityRelationship = 3
```
### Entity

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Entity.</p>


```csharp
Entity = 1
```
### Provenance

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Provenance.</p>


```csharp
Provenance = 4
```
### Relationship

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Relationship.</p>


```csharp
Relationship = 2
```
### Unspecified

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.yml" sourcestartlinenumber="1">Unspecified.</p>


```csharp
Unspecified = 0
```


