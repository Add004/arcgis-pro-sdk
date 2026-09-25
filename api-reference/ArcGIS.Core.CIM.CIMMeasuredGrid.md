# CIMMeasuredGrid

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Represents a measured grid of the mapFrame.</p>


## Object Signature

```csharp
public class CIMMeasuredGrid : CIMMapGrid, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMeasuredGrid()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Represents a measured grid of the mapFrame.</p>


```csharp
public CIMMeasuredGrid()
```
### ClipUTMZone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to clip the grid to the UTM zone. If the measured grid is not defined in one of the UTM coordinates, then this property is irrelevant.</p>


```csharp
public bool ClipUTMZone { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMeasuredGrid.</p>


```csharp
public CIMMeasuredGrid Clone()
```
### CustomOrigin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Gets or sets the custom origin of the measured grid.</p>


```csharp
public MapPoint CustomOrigin { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Reconstructs the CIMMeasuredGrid with a specified state from a JSON encoding.</p>


```csharp
public static CIMMeasuredGrid FromJson(string json, JsonDeserializationSettings settings = null)
```
### GetProjectedCoordinateSystem()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Get the Projected Coordinate System of the CIMMeasuredGrid.</p>


```csharp
public SpatialReference GetProjectedCoordinateSystem()
```
### GridLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Gets or sets the gridLines of the measured grid.</p>


```csharp
public CIMGridLine[] GridLines { get; set; }
```
### IsAutoScaled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to auto-scale the grid.</p>


```csharp
public bool IsAutoScaled { get; set; }
```
### ProjectedCoordinateSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Gets or sets the projected coordinate system of the grid.</p>


```csharp
public ProjectedCoordinateSystem ProjectedCoordinateSystem { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SetProjectedCoordinateSystem(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Set the Projected Coordinate System of the CIMMeasuredGrid.</p>


```csharp
public void SetProjectedCoordinateSystem(SpatialReference sr)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMeasuredGrid and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMapClipShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the clip shape of the map (if set) as the grid boundary.</p>


```csharp
public bool UseMapClipShape { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeasuredGrid.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


