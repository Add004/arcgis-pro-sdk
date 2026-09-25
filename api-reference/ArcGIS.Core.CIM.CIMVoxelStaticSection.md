# CIMVoxelStaticSection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Represents a voxel static section.</p>


## Object Signature

```csharp
public class CIMVoxelStaticSection : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelStaticSection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Represents a voxel static section.</p>


```csharp
public CIMVoxelStaticSection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelStaticSection.</p>


```csharp
public CIMVoxelStaticSection Clone()
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this section is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### Format

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the section format.</p>


```csharp
public CIMVoxelFormat Format { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelStaticSection with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelStaticSection FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the height.</p>


```csharp
public int Height { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the section ID, which must be unique among all sections in the layer.</p>


```csharp
public int ID { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the section name.</p>


```csharp
public string Name { get; set; }
```
### Plane

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the section plane.</p>


```csharp
public CIMVoxelPlane Plane { get; set; }
```
### RasterURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the raster.</p>


```csharp
public string RasterURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Slices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets a collection of slices which define the volume for the section.</p>


```csharp
public CIMVoxelPlane[] Slices { get; set; }
```
### TimeIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the time index that this section was created from for the variable.</p>


```csharp
public int TimeIndex { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelStaticSection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the variable that the section is associated with.</p>


```csharp
public string Variable { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the section is visible.</p>


```csharp
public bool Visible { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Gets or sets the width.</p>


```csharp
public int Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStaticSection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


