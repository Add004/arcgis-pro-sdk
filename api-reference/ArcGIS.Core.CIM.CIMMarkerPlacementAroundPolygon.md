# CIMMarkerPlacementAroundPolygon

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Represents marker placement around polygon which places a marker on a specific position on the polygon outline.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementAroundPolygon : CIMMarkerFillPlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAroundPolygon()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Represents marker placement around polygon which places a marker on a specific position on the polygon outline.</p>


```csharp
public CIMMarkerPlacementAroundPolygon()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementAroundPolygon.</p>


```csharp
public CIMMarkerPlacementAroundPolygon Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementAroundPolygon with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementAroundPolygon FromJson(string json, JsonDeserializationSettings settings = null)
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Gets or sets the offset from the polygon edge. Negative numbers offset toward the inside of the polygon.</p>


```csharp
public double Offset { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Gets or sets the position of the marker around the polygon.</p>


```csharp
public PlacementAroundPolygonPosition Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementAroundPolygon and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAroundPolygon.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


