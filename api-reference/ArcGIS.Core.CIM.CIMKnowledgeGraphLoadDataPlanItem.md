# CIMKnowledgeGraphLoadDataPlanItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Load Data Plan Item.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphLoadDataPlanItem : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphLoadDataPlanItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Load Data Plan Item.</p>


```csharp
public CIMKnowledgeGraphLoadDataPlanItem()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphLoadDataPlanItem.</p>


```csharp
public CIMKnowledgeGraphLoadDataPlanItem Clone()
```
### Configuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Gets or sets the Data Loading Configuration referenced by this Plan Item.</p>


```csharp
public CIMKnowledgeGraphDataLoadingConfiguration Configuration { get; set; }
```
### EntityDefinitionPositions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Gets or sets the entity definition positions referenced by this Plan Item.</p>


```csharp
public CIMKnowledgeGraphEntityDefinitionPosition[] EntityDefinitionPositions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphLoadDataPlanItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphLoadDataPlanItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceTableDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Gets or sets the Data Connection to the source table.</p>


```csharp
public CIMDataConnection SourceTableDataConnection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphLoadDataPlanItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlanItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


