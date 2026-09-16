# CIMKnowledgeGraphLinkChartProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Link Chart Properties object.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphLinkChartProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphLinkChartProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Link Chart Properties object.</p>


```csharp
public CIMKnowledgeGraphLinkChartProperties()
```
### AggregatedLinksURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing a serialized representation of the internal AggregatedLinks table.</p>


```csharp
public string AggregatedLinksURI { get; set; }
```
### AggregatedNodesURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing a serialized representation of the internal AggregatedNodes table.</p>


```csharp
public string AggregatedNodesURI { get; set; }
```
### AutoCollapseRelationships

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this Link Chart automatically collapses eligible relationships.</p>


```csharp
public bool AutoCollapseRelationships { get; set; }
```
### CentralityConfiguration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets the Configuration for Centrality computation in this Link Chart.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="3">Centrality scores found in the Nodes and AggregatedNodes tables were computed using this Configuration.</p>


```csharp
public CIMKnowledgeGraphLinkChartCentralityConfiguration CentralityConfiguration { get; set; }
```
### CentralityIsUpToDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the Centrality scores found in the Nodes and AggregatedNodes tables
were computed using the current Link Chart topology.</p>


```csharp
public bool CentralityIsUpToDate { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphLinkChartProperties.</p>


```csharp
public CIMKnowledgeGraphLinkChartProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphLinkChartProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphLinkChartProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LastUsedLayout

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets information about the last used layout.</p>


```csharp
public CIMKnowledgeLinkChartLayout LastUsedLayout { get; set; }
```
### LinksURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing a serialized representation of the internal Links table.</p>


```csharp
public string LinksURI { get; set; }
```
### NodesURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing a serialized representation of the internal Nodes table.</p>


```csharp
public string NodesURI { get; set; }
```
### NonspatialDataDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Gets or sets the Nonspatial Data Display information in this Link Chart.</p>


```csharp
public CIMKnowledgeNonspatialDataDisplay NonspatialDataDisplay { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphLinkChartProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLinkChartProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


