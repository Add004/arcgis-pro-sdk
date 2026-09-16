# CIMKnowledgeGraphLoadDataPlan

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Load Data Plan.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphLoadDataPlan : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphLoadDataPlan()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Load Data Plan.</p>


```csharp
public CIMKnowledgeGraphLoadDataPlan()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphLoadDataPlan.</p>


```csharp
public CIMKnowledgeGraphLoadDataPlan Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphLoadDataPlan with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphLoadDataPlan FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Gets or sets the name of the Load Data Plan.
Names are expected to be unique within an Investigation.</p>


```csharp
public string Name { get; set; }
```
### PlanItems

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Gets or sets the Load Data Plan Items referenced by this Plan.</p>


```csharp
public CIMKnowledgeGraphLoadDataPlanItem[] PlanItems { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphLoadDataPlan and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLoadDataPlan.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


