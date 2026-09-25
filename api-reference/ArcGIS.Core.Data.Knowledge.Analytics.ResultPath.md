# ResultPath

- Type: struct
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">Gets the representation of a single path returned by the Filtered Find Paths algorithm.</p>


## Object Signature

```csharp
public readonly struct ResultPath
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">The path is a sequence of relationships groups. Relationship groups that have more than one
relationship contain &quot;parallel&quot; relationships, i.e relationships between the same two entities.<br>
Refer to <xref href="ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphFilteredFindPathsResults.MaterializePath(System.Int64)" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### ResultPath(List&lt;PathRelationshipGroup&gt;, long, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">Gets the representation of a single path returned by the Filtered Find Paths algorithm.</p>


```csharp
public ResultPath(List<PathRelationshipGroup> relationshipGroups, long pathLength, double minCost, double maxCost)
```
### Length

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">Gets the length of the path.</p>


```csharp
public readonly long Length
```
### MaxCost

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">Gets the maximum path cost.</p>


```csharp
public readonly double MaxCost
```
### MinCost

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">Gets the minimum path cost.</p>


```csharp
public readonly double MinCost
```
### RelationshipGroups

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.ResultPath.yml" sourcestartlinenumber="1">Gets the relationship groups of the path.</p>


```csharp
public readonly List<PathRelationshipGroup> RelationshipGroups
```


