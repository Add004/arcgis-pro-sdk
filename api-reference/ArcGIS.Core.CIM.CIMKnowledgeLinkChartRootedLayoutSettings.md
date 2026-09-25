# CIMKnowledgeLinkChartRootedLayoutSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Contains settings to be used in rooted layout calculations.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="3">Rooted layouts are layouts that can handle root entities (tree, radial tree and hierarchical layouts).</p>


## Object Signature

```csharp
public class CIMKnowledgeLinkChartRootedLayoutSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeLinkChartRootedLayoutSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Contains settings to be used in rooted layout calculations.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="3">Rooted layouts are layouts that can handle root entities (tree, radial tree and hierarchical layouts).</p>


```csharp
public CIMKnowledgeLinkChartRootedLayoutSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeLinkChartRootedLayoutSettings.</p>


```csharp
public CIMKnowledgeLinkChartRootedLayoutSettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeLinkChartRootedLayoutSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeLinkChartRootedLayoutSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RootEntities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the Identifier and type values of entities that serve as roots for the link chart layout.</p>


```csharp
public CIMKnowledgeRecordInstance[] RootEntities { get; set; }
```
### RootEntityGroups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the Identifier and type values of entity groups that serve as roots for the link chart layout.</p>


```csharp
public CIMKnowledgeRecordInstance[] RootEntityGroups { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeLinkChartRootedLayoutSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartRootedLayoutSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


