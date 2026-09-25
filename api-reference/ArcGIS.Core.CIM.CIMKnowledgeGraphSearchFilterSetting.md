# CIMKnowledgeGraphSearchFilterSetting

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Search Filter Setting.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphSearchFilterSetting : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphSearchFilterSetting()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Search Filter Setting.</p>


```csharp
public CIMKnowledgeGraphSearchFilterSetting()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphSearchFilterSetting.</p>


```csharp
public CIMKnowledgeGraphSearchFilterSetting Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphSearchFilterSetting with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphSearchFilterSetting FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Scope

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Gets or sets the scope of search.</p>


```csharp
public KnowledgeGraphSearchFilterScope Scope { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphSearchFilterSetting and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Gets or sets the name of types to be included in search filter.</p>


```csharp
public string[] TypeNames { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchFilterSetting.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


