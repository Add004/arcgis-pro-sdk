# CIMKeyframeVoxelPlane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Represents a voxel plane keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeVoxelPlane : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Defines a plane for a voxel layer.</p>


## Members

### CIMKeyframeVoxelPlane()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Represents a voxel plane keyframe.</p>


```csharp
public CIMKeyframeVoxelPlane()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeVoxelPlane.</p>


```csharp
public CIMKeyframeVoxelPlane Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeVoxelPlane with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeVoxelPlane FromJson(string json, JsonDeserializationSettings settings = null)
```
### Orientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets the orientation of the plane around the z axis.</p>


```csharp
public double Orientation { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets the position of the plane relative to the edge of the voxel.</p>


```csharp
public double Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Tilt

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets the tilt of the plane.</p>


```csharp
public double Tilt { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeVoxelPlane and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the plane is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelPlane.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


