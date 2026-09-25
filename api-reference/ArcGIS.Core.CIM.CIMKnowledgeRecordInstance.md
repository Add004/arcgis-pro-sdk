# CIMKnowledgeRecordInstance

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">A Knowledge record instance is an entity or a relationship.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="3">In Pro link charts, users can define groups of record instances, where all records
in a group have the same type name.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="6">Depending on the context, CIMKnowledgeRecordInstance represents either a Knowledge record instance
or a group of Knowledge record instances.</p>


## Object Signature

```csharp
public class CIMKnowledgeRecordInstance : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeRecordInstance()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">A Knowledge record instance is an entity or a relationship.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="3">In Pro link charts, users can define groups of record instances, where all records
in a group have the same type name.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="6">Depending on the context, CIMKnowledgeRecordInstance represents either a Knowledge record instance
or a group of Knowledge record instances.</p>


```csharp
public CIMKnowledgeRecordInstance()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeRecordInstance.</p>


```csharp
public CIMKnowledgeRecordInstance Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeRecordInstance with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeRecordInstance FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Gets or sets the ID of the record instance. The ID cannot be null.</p>


```csharp
public object ID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeRecordInstance and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Gets or sets the type name of the record instance.</p>


```csharp
public string TypeName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeRecordInstance.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


