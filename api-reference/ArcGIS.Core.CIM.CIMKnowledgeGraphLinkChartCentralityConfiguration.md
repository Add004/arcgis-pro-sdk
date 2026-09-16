# CIMKnowledgeGraphLinkChartCentralityConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Represents the Centrality computation options in a Knowledge Graph Link Chart.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="3">Several measures of centrality are supported:
Degree, Indegree, Outdegree, PageRank, Eigenvector, Coreness, Betweenness, Closeness and Harmonic.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="6">These measures fall in two broad categories:
degree based measures are Degree, Indegree, Outdegree, PageRank, Eigenvector and Coreness
while shortest paths based measures are Betweenness, Closeness and Harmonic.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="10">The &quot;importance&quot; relationship weight is taken into account in degree based measures:
a relationship with higher importance will increase the centrality scores of nearby related entities.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="13">The &quot;cost&quot; relationship weight is taken into account in shortest paths based measures:
a relationship with higher cost will decrease the centrality scores of nearby related entities.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphLinkChartCentralityConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphLinkChartCentralityConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Represents the Centrality computation options in a Knowledge Graph Link Chart.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="3">Several measures of centrality are supported:
Degree, Indegree, Outdegree, PageRank, Eigenvector, Coreness, Betweenness, Closeness and Harmonic.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="6">These measures fall in two broad categories:
degree based measures are Degree, Indegree, Outdegree, PageRank, Eigenvector and Coreness
while shortest paths based measures are Betweenness, Closeness and Harmonic.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="10">The &quot;importance&quot; relationship weight is taken into account in degree based measures:
a relationship with higher importance will increase the centrality scores of nearby related entities.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="13">The &quot;cost&quot; relationship weight is taken into account in shortest paths based measures:
a relationship with higher cost will decrease the centrality scores of nearby related entities.</p>


```csharp
public CIMKnowledgeGraphLinkChartCentralityConfiguration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphLinkChartCentralityConfiguration.</p>


```csharp
public CIMKnowledgeGraphLinkChartCentralityConfiguration Clone()
```
### ComputeShortestPathsBasedMeasures

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the shortest paths based measures will be computed.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="3">When true, all measures are computed.
When false, all measures except betweenness, Closeness, Harmonic are computed.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="6">This setting exists because shortest paths based measures can be costly to compute for larger graphs.</p>


```csharp
public bool ComputeShortestPathsBasedMeasures { get; set; }
```
### DefaultRelationshipCost

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the default cost of a relationship.</p>


```csharp
public double DefaultRelationshipCost { get; set; }
```
### DefaultRelationshipImportance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the default importance of a relationship.</p>


```csharp
public double DefaultRelationshipImportance { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphLinkChartCentralityConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphLinkChartCentralityConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludeDocumentEntities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether entities of type 'Document' are considered to be
part of the graph for centrality computations.</p>


```csharp
public bool IncludeDocumentEntities { get; set; }
```
### MultiedgeFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the multiedge factor. Acceptable values lie in [0, 1].</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="3">In centrality computations, we reduce parallel relationships of a graph to a single edge.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="5">The computation of the importance of the single edge depends on the value of MultiedgeFactor.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="7">If MultiedgeFactor is 0, the importance of the single edge is the average of parallel relationships.
If MultiedgeFactor is 1, the importance of the single edge is the sum of importances of parallel relationships.
For values of MultiedgeFactor between 0 and 1, the importance of the single edge is linearly interpolated.</p>


```csharp
public double MultiedgeFactor { get; set; }
```
### Normalization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the scores normalization.</p>


```csharp
public CentralityScoresNormalization Normalization { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipCostProperty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the property defining the cost of a relationship.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="3">When the string is empty, or the property doesn't exist, or the property value is null,
the default relationship cost is used instead.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="6">Negative property values are ignored and replaced by zero.</p>


```csharp
public string RelationshipCostProperty { get; set; }
```
### RelationshipImportanceProperty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the property defining the importance of a relationship.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="3">When the string is empty, or the property doesn't exist, or the property value is null,
the default relationship importance is used instead.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="6">Negative property values are ignored and replaced by zero.</p>


```csharp
public string RelationshipImportanceProperty { get; set; }
```
### RelationshipsInterpretation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Gets or sets the relationships interpretation.</p>


```csharp
public CentralityRelationshipInterpretation RelationshipsInterpretation { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphLinkChartCentralityConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartCentralityConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


