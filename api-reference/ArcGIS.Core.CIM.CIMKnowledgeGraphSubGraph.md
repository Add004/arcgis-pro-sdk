# CIMKnowledgeGraphSubGraph

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Represents a subgraph of a Knowledge Graph, defined by entity and relationship filters.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphSubGraph : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphSubGraph()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Represents a subgraph of a Knowledge Graph, defined by entity and relationship filters.</p>


```csharp
public CIMKnowledgeGraphSubGraph()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphSubGraph.</p>


```csharp
public CIMKnowledgeGraphSubGraph Clone()
```
### EntityFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Gets or sets the entity filters of the subgraph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="3">The entities of the subgraph are the entities included by &quot;include&quot; filters
(or all entities if there is no &quot;include&quot; filter),
except entities excluded by &quot;exclude&quot; filters.</p>


```csharp
public CIMKnowledgeGraphNamedTypeFilter[] EntityFilters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphSubGraph with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphSubGraph FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Gets or sets the relationship filters of the subgraph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="3">The relationships of the subgraph are the relationships included by &quot;include&quot; filters
(or all relationships if there is no &quot;include&quot; filter),
except relationships excluded by &quot;exclude&quot; filters and relationships involving at least one entity that is not in the subgraph.</p>


```csharp
public CIMKnowledgeGraphNamedTypeFilter[] RelationshipFilters { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphSubGraph and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


