# CIMSegmentationTargetGroupDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Represents a document used for saving target group.</p>


## Object Signature

```csharp
public class CIMSegmentationTargetGroupDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSegmentationTargetGroupDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Represents a document used for saving target group.</p>


```csharp
public CIMSegmentationTargetGroupDocument()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSegmentationTargetGroupDocument.</p>


```csharp
public CIMSegmentationTargetGroupDocument Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMSegmentationTargetGroupDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMSegmentationTargetGroupDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TargetGroup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Gets or sets the target group.</p>


```csharp
public CIMSegmentationTargetGroup TargetGroup { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSegmentationTargetGroupDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationTargetGroupDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


