# CIMVoxelPlane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Represents a voxel plane.</p>


## Object Signature

```csharp
public class CIMVoxelPlane : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelPlane()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Represents a voxel plane.</p>


```csharp
public CIMVoxelPlane()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelPlane.</p>


```csharp
public CIMVoxelPlane Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelPlane with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelPlane FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets the ID.</p>


```csharp
public string ID { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets the plane's name.</p>


```csharp
public string Name { get; set; }
```
### Normal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets the direction vector of the plane, which is a unit vector representing the normal to the plane.</p>


```csharp
public MapPoint Normal { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets a point on the plane, specified in voxel coordinates.</p>


```csharp
public MapPoint Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelPlane and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the plane is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelPlane.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


