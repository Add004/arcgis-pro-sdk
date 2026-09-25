# CIMFilteredFindPathsStatistics

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Represents the statistics related to a Filtered Find Paths search.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="3">It contains the size of the local graph, and the number of openCypher &quot;expansion&quot; queries that have been issued
to construct the local graph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="6">The local graph is an in-memory graph used for pathfinding where
a node represents an entity in the Knowledge Graph and an edge represents
one or many parallel relationships in the Knowledge Graph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="10">The local graph typically contains (much) less nodes than the Knowledge Graph, but enough nodes and edges
to ensure that the pathfinding results are accurate.
For example, to guarantee that all paths of length up to 'L' between 'A' and 'B' are present in the local graph,
we ensure that the sum of counts of &quot;expansion&quot; queries related to 'A' and 'B' is greater or equal to 'L'.</p>


## Object Signature

```csharp
public class CIMFilteredFindPathsStatistics : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFilteredFindPathsStatistics()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Represents the statistics related to a Filtered Find Paths search.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="3">It contains the size of the local graph, and the number of openCypher &quot;expansion&quot; queries that have been issued
to construct the local graph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="6">The local graph is an in-memory graph used for pathfinding where
a node represents an entity in the Knowledge Graph and an edge represents
one or many parallel relationships in the Knowledge Graph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="10">The local graph typically contains (much) less nodes than the Knowledge Graph, but enough nodes and edges
to ensure that the pathfinding results are accurate.
For example, to guarantee that all paths of length up to 'L' between 'A' and 'B' are present in the local graph,
we ensure that the sum of counts of &quot;expansion&quot; queries related to 'A' and 'B' is greater or equal to 'L'.</p>


```csharp
public CIMFilteredFindPathsStatistics()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFilteredFindPathsStatistics.</p>


```csharp
public CIMFilteredFindPathsStatistics Clone()
```
### CountDestinationExpansionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Gets or sets the count of expansion queries that were done to discover the neighborhood of some destination entities.</p>


```csharp
public long CountDestinationExpansionQueries { get; set; }
```
### CountLocalGraphEdges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Gets or sets the count of edges in the local graph.</p>


```csharp
public long CountLocalGraphEdges { get; set; }
```
### CountLocalGraphNodes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Gets or sets the count of nodes in the local graph.</p>


```csharp
public long CountLocalGraphNodes { get; set; }
```
### CountOriginExpansionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Gets or sets the count of expansion queries that were done to discover the neighborhood of some origin entities.</p>


```csharp
public long CountOriginExpansionQueries { get; set; }
```
### CountWaypointsExpansionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Gets or sets the count of expansion queries that were done to discover the neighborhood of entity or relationship waypoints.</p>


```csharp
public long CountWaypointsExpansionQueries { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Reconstructs the CIMFilteredFindPathsStatistics with a specified state from a JSON encoding.</p>


```csharp
public static CIMFilteredFindPathsStatistics FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFilteredFindPathsStatistics and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsStatistics.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


