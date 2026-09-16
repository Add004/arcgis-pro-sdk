# CIMMapStereoProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Represents map stereo properties.</p>


## Object Signature

```csharp
public class CIMMapStereoProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapStereoProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Represents map stereo properties.</p>


```csharp
public CIMMapStereoProperties()
```
### AdjustColorizersInSync

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether adjustments to either colorizer should be synced to the other.</p>


```csharp
public bool AdjustColorizersInSync { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapStereoProperties.</p>


```csharp
public CIMMapStereoProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMapStereoProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapStereoProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsInverted

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the left and right images of the stereo model should be swapped.</p>


```csharp
public bool IsInverted { get; set; }
```
### IsStereoCursorFixed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the cursor of the stereo model is fixed.</p>


```csharp
[Obsolete("IsStereoCursorFixed is deprecated at 3.7. This property is obsolete.")]
public bool IsStereoCursorFixed { get; set; }
```
### LeftImage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the left image of the stereo pair.</p>


```csharp
public CIMDataConnection LeftImage { get; set; }
```
### LeftImageColorizer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the colorizer for the left image.</p>


```csharp
public CIMRasterColorizer LeftImageColorizer { get; set; }
```
### LeftImageID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the OID of the left image of the current stereo model in a collection.</p>


```csharp
public long LeftImageID { get; set; }
```
### Orientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the stereo model display orientation.</p>


```csharp
public StereoOrientation Orientation { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RightImage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the right image of the stereo pair.</p>


```csharp
public CIMDataConnection RightImage { get; set; }
```
### RightImageColorizer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the colorizer for the right image.</p>


```csharp
public CIMRasterColorizer RightImageColorizer { get; set; }
```
### RightImageID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the OID of the right image of the current stereo model in a collection.</p>


```csharp
public long RightImageID { get; set; }
```
### SourceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the stereo source type.</p>


```csharp
public StereoSourceType SourceType { get; set; }
```
### StereoModelCollection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the data connection to the source stereo model collection.</p>


```csharp
public CIMDataConnection StereoModelCollection { get; set; }
```
### StereoModelDisplayMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the stereo model display mode.</p>


```csharp
public StereoModelDisplayMode StereoModelDisplayMode { get; set; }
```
### StereoModelFilterName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the current stereo model filter.</p>


```csharp
public string StereoModelFilterName { get; set; }
```
### StereoModelFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the stereo model filter(s).</p>


```csharp
public CIMStereoModelFilter[] StereoModelFilters { get; set; }
```
### TerrainFollowingDEM

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Gets or sets the Digital Elevation Model (DEM) used by cursor for terrain following.</p>


```csharp
public CIMDataConnection TerrainFollowingDEM { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapStereoProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapStereoProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


