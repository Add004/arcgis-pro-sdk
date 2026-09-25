# CIMLinkChartLinkLabelingInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Represents the link chart link labeling information.</p>


## Object Signature

```csharp
public class CIMLinkChartLinkLabelingInfo : CIMLinkChartLabelingInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartLinkLabelingInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Represents the link chart link labeling information.</p>


```csharp
public CIMLinkChartLinkLabelingInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartLinkLabelingInfo.</p>


```csharp
public CIMLinkChartLinkLabelingInfo Clone()
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartLinkLabelingInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartLinkLabelingInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelPlacement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets the link label placement.</p>


```csharp
public LinkChartLinkLabelPlacement LabelPlacement { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartLinkLabelingInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLinkLabelingInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


