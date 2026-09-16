# CIMLinkChartLinkDrawingInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Represents the link chart link drawing information.</p>


## Object Signature

```csharp
public class CIMLinkChartLinkDrawingInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartLinkDrawingInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Represents the link chart link drawing information.</p>


```csharp
public CIMLinkChartLinkDrawingInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartLinkDrawingInfo.</p>


```csharp
public CIMLinkChartLinkDrawingInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartLinkDrawingInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartLinkDrawingInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### LinkColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets link color.</p>


```csharp
public CIMColor LinkColor { get; set; }
```
### LinkDashStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets a value for the link dash style.</p>


```csharp
public LinkChartLinkDashStyle LinkDashStyle { get; set; }
```
### LinkWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets a value for the link width.</p>


```csharp
public int LinkWidth { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the directional arrowhead of a link.</p>


```csharp
public bool ShowDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartLinkDrawingInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkDrawingInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


