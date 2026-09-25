# CIMKeyframeSurface

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Represents a surface keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeSurface : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKeyframeSurface()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Represents a surface keyframe.</p>


```csharp
public CIMKeyframeSurface()
```
### BaseSources

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets the elevation sources.</p>


```csharp
public CIMKeyframeElevationSource[] BaseSources { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeSurface.</p>


```csharp
public CIMKeyframeSurface Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeSurface with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeSurface FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SurfaceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets the id for the surface.</p>


```csharp
public string SurfaceID { get; set; }
```
### SwipeDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets the direction to clip from an edge.</p>


```csharp
public SwipeDirection SwipeDirection { get; set; }
```
### SwipePercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets the amount of the visible area to clip.</p>


```csharp
public double SwipePercent { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeSurface and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Transition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the surface.</p>


```csharp
public AnimationTransition Transition { get; set; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets the vertical exaggeration for the surface.</p>


```csharp
public double VerticalExaggeration { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the surface is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeSurface.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


