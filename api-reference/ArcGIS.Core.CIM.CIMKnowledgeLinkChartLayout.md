# CIMKnowledgeLinkChartLayout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Represents a Knowledge Link Chart Layout Info object.</p>


## Object Signature

```csharp
public class CIMKnowledgeLinkChartLayout : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeLinkChartLayout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Represents a Knowledge Link Chart Layout Info object.</p>


```csharp
public CIMKnowledgeLinkChartLayout()
```
### Algorithm

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Gets or sets the layout algorithm.</p>


```csharp
public KnowledgeLinkChartLayoutAlgorithm Algorithm { get; set; }
```
### AutoApply

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layout is automatically redone when a setting value changes.</p>


```csharp
public bool AutoApply { get; set; }
```
### ChronologicalLayoutSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Gets or sets the chronological layout settings.</p>


```csharp
public CIMKnowledgeLinkChartChronologicalLayoutSettings ChronologicalLayoutSettings { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeLinkChartLayout.</p>


```csharp
public CIMKnowledgeLinkChartLayout Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeLinkChartLayout with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeLinkChartLayout FromJson(string json, JsonDeserializationSettings settings = null)
```
### OrganicLayoutSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Gets or sets the organic layout settings.</p>


```csharp
public CIMKnowledgeLinkChartOrganicLayoutSettings OrganicLayoutSettings { get; set; }
```
### PreserveExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the current Link Chart extent is preserved
by the layout (only applies to Chronological and Geographical layouts).</p>


```csharp
public bool PreserveExtent { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RootedLayoutSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Gets or sets the rooted layout settings.</p>


```csharp
public CIMKnowledgeLinkChartRootedLayoutSettings RootedLayoutSettings { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeLinkChartLayout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartLayout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


