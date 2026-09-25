# PathRelationshipGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Represents a group of parallel relationships used in a path.
Parallel relationships are relationships between the same two entities.</p>


## Object Signature

```csharp
public class PathRelationshipGroup
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">To support zero-length paths, by convention when
<xref href="ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.FirstEntity" data-throw-if-not-resolved="false"></xref> is equal to <xref href="ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.SecondEntity" data-throw-if-not-resolved="false"></xref>, then <xref href="ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.Relationships" data-throw-if-not-resolved="false"></xref> is empty
and this object represents a single entity of the path (the only entity of the path).</p>


## Members

### PathRelationshipGroup(Entity, Entity, List&lt;PathRelationship&gt;, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Represents a group of parallel relationships used in a path.
Parallel relationships are relationships between the same two entities.</p>


```csharp
public PathRelationshipGroup(Entity firstEntity, Entity secondEntity, List<PathRelationship> relationships, double minCost, double maxCost)
```
### FirstEntity

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Gets the entity closest to the beginning of the path.</p>


```csharp
public readonly Entity FirstEntity
```
### MaxCost

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Gets the maximum cost of relationships in this group.</p>


```csharp
public readonly double MaxCost
```
### MinCost

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Gets the minimum cost of relationships in this group.</p>


```csharp
public readonly double MinCost
```
### Relationships

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Gets the relationships in this group.<br></p>


```csharp
public readonly List<PathRelationship> Relationships
```
### SecondEntity

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathRelationshipGroup.yml" sourcestartlinenumber="1">Gets the entity closest to the end of the path.</p>


```csharp
public readonly Entity SecondEntity
```


