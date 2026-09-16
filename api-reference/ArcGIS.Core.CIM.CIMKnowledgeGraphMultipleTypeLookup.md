# CIMKnowledgeGraphMultipleTypeLookup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Contains the information defining the multiple type entity lookup.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphMultipleTypeLookup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphMultipleTypeLookup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Contains the information defining the multiple type entity lookup.</p>


```csharp
public CIMKnowledgeGraphMultipleTypeLookup()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphMultipleTypeLookup.</p>


```csharp
public CIMKnowledgeGraphMultipleTypeLookup Clone()
```
### DefaultTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Gets or sets the default type name for the multiple type lookup.
If the lookup fails, this type will be used to create a new entity.
When empty or blank, if the lookup fails, nothing will be created.</p>


```csharp
public string DefaultTypeName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphMultipleTypeLookup with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphMultipleTypeLookup FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphMultipleTypeLookup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeLookups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Gets or sets the information required to look up an entity by matching specific
property values within specific types.</p>


```csharp
public CIMKnowledgeGraphTypeLookup[] TypeLookups { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphMultipleTypeLookup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


