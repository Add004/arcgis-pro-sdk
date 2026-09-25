# CIMKnowledgeGraphNonspatialProperty

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Property used by entities and relationships.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphNonspatialProperty : CIMKnowledgeGraphProperty, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphNonspatialProperty()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Property used by entities and relationships.</p>


```csharp
public CIMKnowledgeGraphNonspatialProperty()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphNonspatialProperty.</p>


```csharp
public CIMKnowledgeGraphNonspatialProperty Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphNonspatialProperty with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphNonspatialProperty FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphNonspatialProperty and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphNonspatialProperty.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


