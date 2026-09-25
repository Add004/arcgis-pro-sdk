# CIMMarkerPlacementInsidePolygon

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Represents marker placement inside a polygon which defines how a polygon is filled with a pattern of markers.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementInsidePolygon : CIMMarkerFillPlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementInsidePolygon()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Represents marker placement inside a polygon which defines how a polygon is filled with a pattern of markers.</p>


```csharp
public CIMMarkerPlacementInsidePolygon()
```
### Clipping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the clipping option which specifies how markers should be clipped at the polygon boundary.</p>


```csharp
public PlacementClip Clipping { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementInsidePolygon.</p>


```csharp
public CIMMarkerPlacementInsidePolygon Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementInsidePolygon with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementInsidePolygon FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the orientation angle that the markers are placed on within the polygon.</p>


```csharp
public double GridAngle { get; set; }
```
### GridType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the grid type which defines how markers are placed.</p>


```csharp
public PlacementGridType GridType { get; set; }
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the marker row offset horizontally.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the marker row offset vertically.</p>


```csharp
public double OffsetY { get; set; }
```
### Randomness

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the randomness of the pattern when markers are placed randomly in a polygon.</p>


```csharp
public double Randomness { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the starting value for generating a random pattern.</p>


```csharp
public int Seed { get; set; }
```
### ShiftOddRows

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether every other row of markers should be shifted to create an offset grid.</p>


```csharp
public bool ShiftOddRows { get; set; }
```
### StepX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the distance between each marker on the X-axis of the grid.</p>


```csharp
public double StepX { get; set; }
```
### StepY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Gets or sets the distance between each marker on the Y-axis of the grid.</p>


```csharp
public double StepY { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementInsidePolygon and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementInsidePolygon.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


