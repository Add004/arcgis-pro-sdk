# CIMViewTrack

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Represents a animation view track.</p>


## Object Signature

```csharp
public class CIMViewTrack : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">The view track will contain the collection of view keyframes that make up the animation.</p>


## Members

### CIMViewTrack()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Represents a animation view track.</p>


```csharp
public CIMViewTrack()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Creates a deep copy of CIMViewTrack.</p>


```csharp
public CIMViewTrack Clone()
```
### DataRateFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the data rate factor. A higher data rate can give better quality, but produces a larger file.</p>


```csharp
public double DataRateFactor { get; set; }
```
### EndFrameTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets what time in the animation to end at for exporting.</p>


```csharp
public double EndFrameTime { get; set; }
```
### ExportType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the export MIME type. Supported formats: video/mp4, video/avi, image/gif, image/jpeg, or image/png.</p>


```csharp
public string ExportType { get; set; }
```
### FrameRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the number of frames per second.</p>


```csharp
public double FrameRate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Reconstructs the CIMViewTrack with a specified state from a JSON encoding.</p>


```csharp
public static CIMViewTrack FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometryStorageURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the URI of the storage for geometries.</p>


```csharp
public string GeometryStorageURI { get; set; }
```
### KeyframeGeometryStorageURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the URI of the storage for keyframes using geometries.</p>


```csharp
public string KeyframeGeometryStorageURI { get; set; }
```
### Keyframes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the collection of view keyframes.</p>


```csharp
public CIMViewKeyframe[] Keyframes { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the name of the track.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceResolutionHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the desired pixel height the animation was made to export at.</p>


```csharp
public int ReferenceResolutionHeight { get; set; }
```
### ReferenceResolutionWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the desired pixel width the animation was made to export at.</p>


```csharp
public int ReferenceResolutionWidth { get; set; }
```
### ScreenGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets the list of graphic overlays used in the animation.</p>


```csharp
public CIMAnimationScreenGraphic[] ScreenGraphics { get; set; }
```
### StartFrameTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Gets or sets what time in the animation to start at for exporting.</p>


```csharp
public double StartFrameTime { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMViewTrack and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewTrack.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


