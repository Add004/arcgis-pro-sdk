# CIMKnowledgeNonspatialDataDisplay

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Represents a Knowledge Nonspatial Data Display object.</p>


## Object Signature

```csharp
public class CIMKnowledgeNonspatialDataDisplay : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeNonspatialDataDisplay()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Represents a Knowledge Nonspatial Data Display object.</p>


```csharp
public CIMKnowledgeNonspatialDataDisplay()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeNonspatialDataDisplay.</p>


```csharp
public CIMKnowledgeNonspatialDataDisplay Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeNonspatialDataDisplay with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeNonspatialDataDisplay FromJson(string json, JsonDeserializationSettings settings = null)
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Gets or sets the display mode.</p>


```csharp
public KnowledgeNonspatialDataDisplayMode Mode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeNonspatialDataDisplay and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeNonspatialDataDisplay.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


