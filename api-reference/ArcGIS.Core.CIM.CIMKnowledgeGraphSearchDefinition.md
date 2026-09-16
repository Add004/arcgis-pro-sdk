# CIMKnowledgeGraphSearchDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Search Definition.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphSearchDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphSearchDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Search Definition.</p>


```csharp
public CIMKnowledgeGraphSearchDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphSearchDefinition.</p>


```csharp
public CIMKnowledgeGraphSearchDefinition Clone()
```
### FilterSetting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Gets or sets search filter setting.</p>


```csharp
public CIMKnowledgeGraphSearchFilterSetting FilterSetting { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphSearchDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphSearchDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Gets or sets user defined name for search.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SearchString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Gets or sets user defined search string.
Search string is based on Lucene syntax.</p>


```csharp
public string SearchString { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphSearchDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSearchDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


