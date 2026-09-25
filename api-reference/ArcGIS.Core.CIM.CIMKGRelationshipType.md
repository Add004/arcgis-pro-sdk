# CIMKGRelationshipType

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Relationship Type.</p>


## Object Signature

```csharp
public class CIMKGRelationshipType : CIMKGType, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGRelationshipType()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Relationship Type.</p>


```csharp
public CIMKGRelationshipType()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGRelationshipType.</p>


```csharp
public CIMKGRelationshipType Clone()
```
### Endpoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Gets or sets the relationship types' endpoints.</p>


```csharp
public CIMKGRelationshipTypeEndpoint[] Endpoints { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Reconstructs the CIMKGRelationshipType with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGRelationshipType FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGRelationshipType and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipType.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


