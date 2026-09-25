# CIMMarkerPlacementAtRatioPositions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Represents marker placement at ratio positions which places a set number of markers along the line or the outline of a polygon.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementAtRatioPositions : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAtRatioPositions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Represents marker placement at ratio positions which places a set number of markers along the line or the outline of a polygon.</p>


```csharp
public CIMMarkerPlacementAtRatioPositions()
```
### BeginPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Gets or sets the distance from the beginning of a line that the marker will be placed.</p>


```csharp
public double BeginPosition { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementAtRatioPositions.</p>


```csharp
public CIMMarkerPlacementAtRatioPositions Clone()
```
### EndPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Gets or sets the distance from the end of a line that the marker will be placed. The ending of a line is determined by the direction in which the line was digitized.</p>


```csharp
public double EndPosition { get; set; }
```
### FlipFirst

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether only the first marker will be rotated 180 degrees.</p>


```csharp
public bool FlipFirst { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementAtRatioPositions with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementAtRatioPositions FromJson(string json, JsonDeserializationSettings settings = null)
```
### PositionArray

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Gets or sets the array of positions.</p>


```csharp
public double[] PositionArray { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementAtRatioPositions and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtRatioPositions.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


