# CIMSegmentationTarget

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Business Analyst segmentation target. Target is a collection of market segments
that are treated as a whole. A user might apply the same marketing strategy to
all segments in a target, for example.</p>


## Object Signature

```csharp
public class CIMSegmentationTarget : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSegmentationTarget()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Business Analyst segmentation target. Target is a collection of market segments
that are treated as a whole. A user might apply the same marketing strategy to
all segments in a target, for example.</p>


```csharp
public CIMSegmentationTarget()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSegmentationTarget.</p>


```csharp
public CIMSegmentationTarget Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Gets or sets the color of the target.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Reconstructs the CIMSegmentationTarget with a specified state from a JSON encoding.</p>


```csharp
public static CIMSegmentationTarget FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Gets or sets the name of target.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SegmentIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Gets or sets the segment IDs of the target.</p>


```csharp
public string[] SegmentIDs { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSegmentationTarget and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTarget.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


