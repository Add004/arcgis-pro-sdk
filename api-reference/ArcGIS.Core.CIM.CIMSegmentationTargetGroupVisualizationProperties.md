# CIMSegmentationTargetGroupVisualizationProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Visualization properties of Business Analyst Segmentation target group.</p>


## Object Signature

```csharp
public class CIMSegmentationTargetGroupVisualizationProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSegmentationTargetGroupVisualizationProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Visualization properties of Business Analyst Segmentation target group.</p>


```csharp
public CIMSegmentationTargetGroupVisualizationProperties()
```
### BaseProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Gets or sets the base profile of the target group.</p>


```csharp
public CIMSegmentationProfile BaseProfile { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSegmentationTargetGroupVisualizationProperties.</p>


```csharp
public CIMSegmentationTargetGroupVisualizationProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMSegmentationTargetGroupVisualizationProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMSegmentationTargetGroupVisualizationProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TargetProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Gets or sets the target profile of the target group.</p>


```csharp
public CIMSegmentationProfile TargetProfile { get; set; }
```
### ThresholdComposition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Gets or sets the Threshold Composition of the target group.</p>


```csharp
public double ThresholdComposition { get; set; }
```
### ThresholdIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Gets or sets the Threshold Index of the target group.</p>


```csharp
public double ThresholdIndex { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSegmentationTargetGroupVisualizationProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupVisualizationProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


