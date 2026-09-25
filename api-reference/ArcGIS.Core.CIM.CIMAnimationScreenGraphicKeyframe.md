# CIMAnimationScreenGraphicKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Properties defining the graphic at a single point in time for the animation.</p>


## Object Signature

```csharp
public class CIMAnimationScreenGraphicKeyframe : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationScreenGraphicKeyframe()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Properties defining the graphic at a single point in time for the animation.</p>


```csharp
public CIMAnimationScreenGraphicKeyframe()
```
### AnchorX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the horizontal placement percent of the graphic anchor position on the viewer (0 is left edge, 1 is right edge).</p>


```csharp
public double AnchorX { get; set; }
```
### AnchorY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the vertical placement percent of the graphic anchor position on the viewer (0 is top edge, 1 is bottom edge).</p>


```csharp
public double AnchorY { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationScreenGraphicKeyframe.</p>


```csharp
public CIMAnimationScreenGraphicKeyframe Clone()
```
### ElementHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the pixel height for the graphic. It applies only to the animation screen graphic that contains a polygon graphic.</p>


```csharp
public double ElementHeight { get; set; }
```
### ElementWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the pixel width for the graphic. It applies only to the animation screen graphic that contains a polygon graphic.</p>


```csharp
public double ElementWidth { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationScreenGraphicKeyframe with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationScreenGraphicKeyframe FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the angle of rotation (in degrees) for the graphic. It applies only to the animation screen graphic that contains a polygon graphic.</p>


```csharp
public double Rotation { get; set; }
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the size multiplier for the graphic.</p>


```csharp
public double Scale { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationScreenGraphicKeyframe and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrackTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the time in seconds relative to the beginning of the track.</p>


```csharp
public double TrackTime { get; set; }
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Gets or sets the transparency of the graphic as a percentage.</p>


```csharp
public double Transparency { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicKeyframe.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


