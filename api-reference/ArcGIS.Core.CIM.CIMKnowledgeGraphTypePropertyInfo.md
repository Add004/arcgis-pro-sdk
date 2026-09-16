# CIMKnowledgeGraphTypePropertyInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type Property Info.
It is primarily used to configure property visibility within the investigation view.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphTypePropertyInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphTypePropertyInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type Property Info.
It is primarily used to configure property visibility within the investigation view.</p>


```csharp
public CIMKnowledgeGraphTypePropertyInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphTypePropertyInfo.</p>


```csharp
public CIMKnowledgeGraphTypePropertyInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphTypePropertyInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphTypePropertyInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the property is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### PropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Gets or sets the name of the property.</p>


```csharp
public string PropertyName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphTypePropertyInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTypePropertyInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


