# CIMKnowledgeGraphTypeLookup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Contains the information required to perform an entity lookup on a specific type.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphTypeLookup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphTypeLookup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Contains the information required to perform an entity lookup on a specific type.</p>


```csharp
public CIMKnowledgeGraphTypeLookup()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphTypeLookup.</p>


```csharp
public CIMKnowledgeGraphTypeLookup Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphTypeLookup with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphTypeLookup FromJson(string json, JsonDeserializationSettings settings = null)
```
### Properties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Gets or sets the properties used in the lookup.  All properties
included must match for the lookup to succeed.</p>


```csharp
public CIMKnowledgeGraphProperty[] Properties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphTypeLookup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Gets or sets the type name used for the lookup.</p>


```csharp
public string TypeName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypeLookup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


