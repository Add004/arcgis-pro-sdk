# CIMMarkerPlacementPolygonCenter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Represents marker placement polygon center which defines how a single marker will be placed within the polygon.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementPolygonCenter : CIMMarkerFillPlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementPolygonCenter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Represents marker placement polygon center which defines how a single marker will be placed within the polygon.</p>


```csharp
public CIMMarkerPlacementPolygonCenter()
```
### ClipAtBoundary

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the marker should be clipped if it extends pasts the boundary of the polygon.</p>


```csharp
public bool ClipAtBoundary { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementPolygonCenter.</p>


```csharp
public CIMMarkerPlacementPolygonCenter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementPolygonCenter with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementPolygonCenter FromJson(string json, JsonDeserializationSettings settings = null)
```
### Method

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Gets or sets the method used to determine the polygon center.</p>


```csharp
public PlacementPolygonCenterMethod Method { get; set; }
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Gets or sets the value which offsets the marker horizontally from the center.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Gets or sets the value which offsets the marker vertically from the center.</p>


```csharp
public double OffsetY { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementPolygonCenter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementPolygonCenter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


