# CIMKnowledgeGraphQueryDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Query Definition.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphQueryDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphQueryDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Query Definition.</p>


```csharp
public CIMKnowledgeGraphQueryDefinition()
```
### BindParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Gets or sets the bind parameters associated with the open cypher query.</p>


```csharp
public CIMDiscreteVariable[] BindParameters { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphQueryDefinition.</p>


```csharp
public CIMKnowledgeGraphQueryDefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphQueryDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphQueryDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Gets or sets user defined name for open cypher query.</p>


```csharp
public string Name { get; set; }
```
### OpenCypherQuery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Gets or sets user defined open cypher query.</p>


```csharp
public string OpenCypherQuery { get; set; }
```
### ProvenanceBehavior

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Gets or sets the query behavior for Provenance.</p>


```csharp
public ProvenanceBehavior ProvenanceBehavior { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphQueryDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphQueryDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


