# CIMReportMapFrameElementProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Represents properties that will be applied to a map frame element in a report.</p>


## Object Signature

```csharp
public class CIMReportMapFrameElementProperties : CIMReportElementFieldProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportMapFrameElementProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Represents properties that will be applied to a map frame element in a report.</p>


```csharp
public CIMReportMapFrameElementProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportMapFrameElementProperties.</p>


```csharp
public CIMReportMapFrameElementProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMReportMapFrameElementProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportMapFrameElementProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### HighlightFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to highlight features in a map frame element.</p>


```csharp
public bool HighlightFeatures { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialMapSeries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Gets or sets the spatial map series properties for a map frame element.</p>


```csharp
public CIMSpatialMapSeries SpatialMapSeries { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportMapFrameElementProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportMapFrameElementProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


