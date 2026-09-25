# CIMKnowledgeGraphNamedTypeFilterByInstances

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Represents a Knowledge Graph named type filter by instances.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphNamedTypeFilterByInstances : CIMKnowledgeGraphNamedTypeFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphNamedTypeFilterByInstances()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Represents a Knowledge Graph named type filter by instances.</p>


```csharp
public CIMKnowledgeGraphNamedTypeFilterByInstances()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphNamedTypeFilterByInstances.</p>


```csharp
public CIMKnowledgeGraphNamedTypeFilterByInstances Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphNamedTypeFilterByInstances with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphNamedTypeFilterByInstances FromJson(string json, JsonDeserializationSettings settings = null)
```
### InstancesIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Gets or sets the ids of the entity/relationship instances represented by the filter.</p>


```csharp
public object[] InstancesIDs { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphNamedTypeFilterByInstances and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


