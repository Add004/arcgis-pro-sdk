# CIMKGRelationshipTypeEndpoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Relationship Type Endpoint.</p>


## Object Signature

```csharp
public class CIMKGRelationshipTypeEndpoint : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGRelationshipTypeEndpoint()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Relationship Type Endpoint.</p>


```csharp
public CIMKGRelationshipTypeEndpoint()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGRelationshipTypeEndpoint.</p>


```csharp
public CIMKGRelationshipTypeEndpoint Clone()
```
### DestinationEntityTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Gets or sets the name of the entity type the relationship type is connected to on its destination side.</p>


```csharp
public string DestinationEntityTypeName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Reconstructs the CIMKGRelationshipTypeEndpoint with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGRelationshipTypeEndpoint FromJson(string json, JsonDeserializationSettings settings = null)
```
### OriginEntityTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Gets or sets the name of the entity type the relationship type is connected to on its origin side.</p>


```csharp
public string OriginEntityTypeName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGRelationshipTypeEndpoint and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGRelationshipTypeEndpoint.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


