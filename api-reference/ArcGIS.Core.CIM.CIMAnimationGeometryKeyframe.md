# CIMAnimationGeometryKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Properties defining the geometry at a single point in time for the animation.</p>


## Object Signature

```csharp
public class CIMAnimationGeometryKeyframe : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationGeometryKeyframe()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Properties defining the geometry at a single point in time for the animation.</p>


```csharp
public CIMAnimationGeometryKeyframe()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationGeometryKeyframe.</p>


```csharp
public CIMAnimationGeometryKeyframe Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationGeometryKeyframe with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationGeometryKeyframe FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometryID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Gets or sets the ID of the CIMAnimationGeometry to be used.</p>


```csharp
public int GeometryID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationGeometryKeyframe and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrackTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Gets or sets the time in seconds relative to the beginning of the animation.</p>


```csharp
public double TrackTime { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryKeyframe.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


