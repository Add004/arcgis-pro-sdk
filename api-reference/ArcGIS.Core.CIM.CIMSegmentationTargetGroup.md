# CIMSegmentationTargetGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Business Analyst target group. Target group represents a collection of targets.</p>


## Object Signature

```csharp
public class CIMSegmentationTargetGroup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSegmentationTargetGroup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Business Analyst target group. Target group represents a collection of targets.</p>


```csharp
public CIMSegmentationTargetGroup()
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets the name of the author of the target group.</p>


```csharp
public string Author { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSegmentationTargetGroup.</p>


```csharp
public CIMSegmentationTargetGroup Clone()
```
### CreationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets creation date of the target group.</p>


```csharp
public TimeInstant CreationDate { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets description of the target group.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Reconstructs the CIMSegmentationTargetGroup with a specified state from a JSON encoding.</p>


```csharp
public static CIMSegmentationTargetGroup FromJson(string json, JsonDeserializationSettings settings = null)
```
### LastRevisionDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets last revision date of the target group.</p>


```csharp
public TimeInstant LastRevisionDate { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets the name of the target group.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SegmentationSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets the segmentation system of the target group.</p>


```csharp
public string SegmentationSystem { get; set; }
```
### Targets

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets the targets of the target group.</p>


```csharp
public CIMSegmentationTarget[] Targets { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSegmentationTargetGroup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisualizationProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Gets or sets visualization properties of the target group.</p>


```csharp
public CIMSegmentationTargetGroupVisualizationProperties VisualizationProperties { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


