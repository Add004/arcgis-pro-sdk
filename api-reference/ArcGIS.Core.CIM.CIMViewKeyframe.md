# CIMViewKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Represents a view keyframe.</p>


## Object Signature

```csharp
public class CIMViewKeyframe : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMViewKeyframe()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Represents a view keyframe.</p>


```csharp
public CIMViewKeyframe()
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the camera keyframe.</p>


```csharp
public CIMKeyframeCamera Camera { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Creates a deep copy of CIMViewKeyframe.</p>


```csharp
public CIMViewKeyframe Clone()
```
### ExploratoryAnalysis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the collection of exploratory analysis.</p>


```csharp
public CIMKeyframeAnalysis[] ExploratoryAnalysis { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Reconstructs the CIMViewKeyframe with a specified state from a JSON encoding.</p>


```csharp
public static CIMViewKeyframe FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the collection of layer keyframes.</p>


```csharp
public CIMKeyframeLayer[] Layers { get; set; }
```
### Range

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the range keyframe.</p>


```csharp
public CIMKeyframeRange Range { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Surfaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the collection of surface keyframes.</p>


```csharp
public CIMKeyframeSurface[] Surfaces { get; set; }
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the time keyframe.</p>


```csharp
public CIMKeyframeTime Time { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMViewKeyframe and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrackTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the value of time in seconds that the keyframe exists in the track.</p>


```csharp
public double TrackTime { get; set; }
```
### Weather

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Gets or sets the weather.</p>


```csharp
public CIMWeatherEffect Weather { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewKeyframe.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


