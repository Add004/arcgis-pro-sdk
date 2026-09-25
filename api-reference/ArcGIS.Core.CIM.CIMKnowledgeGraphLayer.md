# CIMKnowledgeGraphLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Provides access to properties of a Knowledge Graph layer.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Provides access to properties of a Knowledge Graph layer.</p>


```csharp
public CIMKnowledgeGraphLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphLayer.</p>


```csharp
public CIMKnowledgeGraphLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets or sets the layer URIs of the layers in the composite layer.</p>


```csharp
public string[] Layers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


