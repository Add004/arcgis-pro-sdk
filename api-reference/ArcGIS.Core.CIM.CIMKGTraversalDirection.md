# CIMKGTraversalDirection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Filtered Find Paths TraversalDirection.
The filtered find paths algorithm uses traversal directions to specify how relationships are traversed.
When no traversal direction is defined for a specific relationship type, the default traversal direction is used.</p>


## Object Signature

```csharp
public class CIMKGTraversalDirection : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGTraversalDirection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Filtered Find Paths TraversalDirection.
The filtered find paths algorithm uses traversal directions to specify how relationships are traversed.
When no traversal direction is defined for a specific relationship type, the default traversal direction is used.</p>


```csharp
public CIMKGTraversalDirection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGTraversalDirection.</p>


```csharp
public CIMKGTraversalDirection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Reconstructs the CIMKGTraversalDirection with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGTraversalDirection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Gets or sets the relationship type name of the traversal direction object.</p>


```csharp
public string RelationshipTypeName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGTraversalDirection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TraversalDirectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Gets or sets the traversal direction of the traversal direction object.</p>


```csharp
public KGTraversalDirectionType TraversalDirectionType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTraversalDirection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


