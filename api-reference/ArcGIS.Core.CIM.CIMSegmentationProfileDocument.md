# CIMSegmentationProfileDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Represents a document used for saving segmentation profile.</p>


## Object Signature

```csharp
public class CIMSegmentationProfileDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSegmentationProfileDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Represents a document used for saving segmentation profile.</p>


```csharp
public CIMSegmentationProfileDocument()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSegmentationProfileDocument.</p>


```csharp
public CIMSegmentationProfileDocument Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMSegmentationProfileDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMSegmentationProfileDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### Profile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Gets or sets the segmentation profile.</p>


```csharp
public CIMSegmentationProfile Profile { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSegmentationProfileDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfileDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


