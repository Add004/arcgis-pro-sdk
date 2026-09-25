# CIMKnowledgeGraphDataLoadingConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Configuration.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphDataLoadingConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphDataLoadingConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Configuration.</p>


```csharp
public CIMKnowledgeGraphDataLoadingConfiguration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphDataLoadingConfiguration.</p>


```csharp
public CIMKnowledgeGraphDataLoadingConfiguration Clone()
```
### Entities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Gets or sets the entities.</p>


```csharp
public CIMKnowledgeGraphDataLoadingEntity[] Entities { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphDataLoadingConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphDataLoadingConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### MissingDataOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Gets or sets the options for missing data.</p>


```csharp
public CIMKnowledgeGraphDataLoadingMissingDataOptions MissingDataOptions { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Gets or sets the name of the Data Loading Configuration.
Names are expected to be unique within an Investigation.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Relationships

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Gets or sets the relationships.</p>


```csharp
public CIMKnowledgeGraphDataLoadingRelationship[] Relationships { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphDataLoadingConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


