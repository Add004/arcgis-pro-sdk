# CIMSegmentationProfile

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Business Analyst segmentation profile. Segmentation profile represents distribution
of the market (e.g. people or households) between the segments of the segmentation system.
For example, it could represent the distribution of the customer base between the segments.
Segmentation profile can include the volumetric information in addition to the counts,
e.g. it could also provide the distribution of the sales between segments.</p>


## Object Signature

```csharp
public class CIMSegmentationProfile : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSegmentationProfile()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Business Analyst segmentation profile. Segmentation profile represents distribution
of the market (e.g. people or households) between the segments of the segmentation system.
For example, it could represent the distribution of the customer base between the segments.
Segmentation profile can include the volumetric information in addition to the counts,
e.g. it could also provide the distribution of the sales between segments.</p>


```csharp
public CIMSegmentationProfile()
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets the name of the author of the segmentation profile.</p>


```csharp
public string Author { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSegmentationProfile.</p>


```csharp
public CIMSegmentationProfile Clone()
```
### Counts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets the counts of the segmentation profile.</p>


```csharp
public int[] Counts { get; set; }
```
### CreationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets creation date of the segmentation profile.</p>


```csharp
public TimeInstant CreationDate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Reconstructs the CIMSegmentationProfile with a specified state from a JSON encoding.</p>


```csharp
public static CIMSegmentationProfile FromJson(string json, JsonDeserializationSettings settings = null)
```
### HasVolumetricData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the segmentation profile contains volumetric information.</p>


```csharp
public bool HasVolumetricData { get; set; }
```
### LastRevisionDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets last revision date of the segmentation profile.</p>


```csharp
public TimeInstant LastRevisionDate { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets the name of the segmentation profile.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SegmentationBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets segmentation base of the segmentation profile.</p>


```csharp
public string SegmentationBase { get; set; }
```
### SegmentationSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets the segmentation system of the segmentation profile.</p>


```csharp
public string SegmentationSystem { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSegmentationProfile and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VolumetricValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Gets or sets the volumetric values of the segmentation profile.</p>


```csharp
public double[] VolumetricValues { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSegmentationProfile.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


