# KnowledgeGraphFilteredFindPathsResults

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gives access to paths found by the Filtered Find Paths algorithm, as well as pathfinding warnings and statistics.</p>


## Object Signature

```csharp
public class KnowledgeGraphFilteredFindPathsResults
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Individual paths can be materialized using <xref href="ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.MaterializePath(System.Int64)" data-throw-if-not-resolved="false"></xref>.<br><br>
For performance, if you are only interested in the entities and relationships of paths,
use <xref href="ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.ExtractPathsEntitiesAndRelationships(System.Collections.Generic.SortedSet%7bSystem.UInt64%7d)" data-throw-if-not-resolved="false"></xref> instead of
materializing paths.<br><br></p>


## Members

### KnowledgeGraphFilteredFindPathsResults()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gives access to paths found by the Filtered Find Paths algorithm, as well as pathfinding warnings and statistics.</p>


```csharp
public KnowledgeGraphFilteredFindPathsResults()
```
### CountDestinationExpansionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets the count of one-hop away expansion queries (from destination entities) that have been issued to build the in-memory local graph used for pathfinding.</p>


```csharp
public ulong CountDestinationExpansionQueries { get; }
```
### CountLocalGraphEdges

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets the count of edges in the in-memory local graph used for pathfinding.</p>


```csharp
public ulong CountLocalGraphEdges { get; }
```
### CountLocalGraphNodes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets the count of nodes in the in-memory local graph used for pathfinding.</p>


```csharp
public ulong CountLocalGraphNodes { get; }
```
### CountOriginExpansionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets the count of one-hop away expansion queries (from origin entities) that have been issued to build the in-memory local graph used for pathfinding.</p>


```csharp
public ulong CountOriginExpansionQueries { get; }
```
### CountPaths

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets the count of paths found by Filtered Find Paths.</p>


```csharp
public long CountPaths { get; }
```
### CountWaypointsExpansionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets the count of one-hop away expansion queries (from waypoint entities) that have been issued to build the in-memory local graph used for pathfinding.</p>


```csharp
public ulong CountWaypointsExpansionQueries { get; }
```
### ExtractPathsEntitiesAndRelationships(SortedSet&lt;ulong&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Computes the entities and relationships associated to all or some of the result paths.</p>


```csharp
public PathsEntitiesAndRelationships ExtractPathsEntitiesAndRelationships(SortedSet<ulong> filterPathIndices)
```
### HasNegativeRelationshipsCostsConvertedToPositiveCosts

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Gets a value indicating whether some negative relationship costs have been converted to positive costs during pathfinding.</p>


```csharp
public bool HasNegativeRelationshipsCostsConvertedToPositiveCosts { get; }
```
### MaterializePath(long)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Returns a materialization of a result path, or null if the path is invalid,
i.e some entities or relationships of the path have been deleted during pathfinding.</p>


```csharp
public ResultPath? MaterializePath(long pathIndex)
```
### NoPathExplanation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">When no path has been found (<xref href="ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.CountPaths" data-throw-if-not-resolved="false"></xref> = 0), this may give an insight as to why no path has been found.</p>


```csharp
public FFPNoPathExplanation NoPathExplanation { get; }
```
### PathIndicesOrderedByIncreasingMaxPathCost

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Returns an array of (max path cost, path index) ordered by increasing &quot;max path cost&quot;.</p>


```csharp
public (double maxCost, long index)[] PathIndicesOrderedByIncreasingMaxPathCost { get; }
```
### PathIndicesOrderedByIncreasingMinPathCost

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Returns an array of (min path cost, path index) ordered by increasing &quot;min path cost&quot;.</p>


```csharp
public (double minCost, long index)[] PathIndicesOrderedByIncreasingMinPathCost { get; }
```
### PathIndicesOrderedByIncreasingPathLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Returns an array of (path length, path index) ordered by increasing &quot;path length&quot;.</p>


```csharp
public (long length, long index)[] PathIndicesOrderedByIncreasingPathLength { get; }
```
### PathsMetrics

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">Returns an array of <xref href="ArcGIS.Core.Data.Knowledge.Analytics.PathMetrics" data-throw-if-not-resolved="false"></xref> indexed by the path index. If the PathMetrics value is null, the path is not valid.</p>


```csharp
public PathMetrics?[] PathsMetrics { get; }
```
### ServiceURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.yml" sourcestartlinenumber="1">URL of the Knowledge Graph service.</p>


```csharp
public string ServiceURL { get; set; }
```


