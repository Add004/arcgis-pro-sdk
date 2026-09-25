# CIMGraticule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Represents a graticule for a map frame.</p>


## Object Signature

```csharp
public class CIMGraticule : CIMMapGrid, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGraticule()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Represents a graticule for a map frame.</p>


```csharp
public CIMGraticule()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGraticule.</p>


```csharp
public CIMGraticule Clone()
```
### CustomOrigin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Gets or sets the custom origin of a graticule.</p>


```csharp
public MapPoint CustomOrigin { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Reconstructs the CIMGraticule with a specified state from a JSON encoding.</p>


```csharp
public static CIMGraticule FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeographicCoordinateSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Gets or sets the spatial reference of a graticule.</p>


```csharp
public GeographicCoordinateSystem GeographicCoordinateSystem { get; set; }
```
### GetGeographicCoordinateSystem()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Get the Geographic Coordinate System of the CIMGraticule.</p>


```csharp
public SpatialReference GetGeographicCoordinateSystem()
```
### GridLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Gets or sets the collection of latitudes and longitudes for a graticule.</p>


```csharp
public CIMGridLine[] GridLines { get; set; }
```
### IsAutoScaled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically adjust the interval of the graticules based on scale of the map.</p>


```csharp
public bool IsAutoScaled { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SetGeographicCoordinateSystem(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Set the Geographic Coordinate System of the CIMGraticule.</p>


```csharp
public void SetGeographicCoordinateSystem(SpatialReference sr)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGraticule and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMapClipShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the clip shape of the map (if set) as the grid boundary.</p>


```csharp
public bool UseMapClipShape { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraticule.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


