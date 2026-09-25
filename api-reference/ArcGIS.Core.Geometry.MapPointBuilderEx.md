# MapPointBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class MapPointBuilderEx : GeometryBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Use the MapPointBuilderEx class to to create and/or modify a MapPoint shape. A MapPoint is based upon the parent Geometry class.
The Geometry class is immutable which means that you can not change its shape once it is created. Hence, the MapPointBuilderEx
provides the way to make changes when working with a MapPoint. Use the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method to
get the MapPoint geometry from the builder.</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="8">The MapPointBuilderEx methods can be called on any thread.</p>


## Members

### MapPointBuilderEx(Coordinate2D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderEx instance with the given coordinates.</p>


```csharp
public MapPointBuilderEx(Coordinate2D coord2D, SpatialReference spatialReference = null)
```
### MapPointBuilderEx(Coordinate3D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderEx instance with the given coordinates.</p>


```csharp
public MapPointBuilderEx(Coordinate3D coordinate3D, SpatialReference spatialReference = null)
```
### MapPointBuilderEx(MapPoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> class from the properties of the input <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapPointBuilderEx(MapPoint point)
```
### MapPointBuilderEx(MapPointBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> class that is a copy of the given builder.</p>


```csharp
public MapPointBuilderEx(MapPointBuilderEx mapPointBuilderEx)
```
### MapPointBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates an empty instance of the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MapPointBuilderEx(SpatialReference spatialReference = null)
```
### MapPointBuilderEx(double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderEx instance with the given X and Y coordinates.</p>


```csharp
public MapPointBuilderEx(double x, double y, SpatialReference spatialReference = null)
```
### MapPointBuilderEx(double, double, bool, double, bool, double, bool, int, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderEx instance with the given X and Y coordinates and
other attributes.</p>


```csharp
public MapPointBuilderEx(double x, double y, bool hasZ, double z, bool hasM, double m, bool hasId, int id, SpatialReference spatialReference = null)
```
### MapPointBuilderEx(double, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderEx instance with the given X, Y, and Z coordinates.</p>


```csharp
public MapPointBuilderEx(double x, double y, double z, SpatialReference spatialReference = null)
```
### MapPointBuilderEx(double, double, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderex instance with the given X, Y, Z and M coordinates.</p>


```csharp
public MapPointBuilderEx(double x, double y, double z, double m, SpatialReference spatialReference = null)
```
### MapPointBuilderEx(double, double, double, double, int, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a new MapPointBuilderEx instance with the given X, Y, Z, M and ID coordinates.</p>


```csharp
public MapPointBuilderEx(double x, double y, double z, double m, int id, SpatialReference spatialReference = null)
```
### CreateMapPoint(Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given coordinates.</p>


```csharp
public static MapPoint CreateMapPoint(Coordinate2D coordinate2D, SpatialReference spatialReference = null)
```
### CreateMapPoint(Coordinate3D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given coordinates.</p>


```csharp
public static MapPoint CreateMapPoint(Coordinate3D coordinate3D, SpatialReference spatialReference = null)
```
### CreateMapPoint(MapPoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a MapPoint instance.</p>


```csharp
public static MapPoint CreateMapPoint(MapPoint point, SpatialReference spatialReference = null)
```
### CreateMapPoint(MapPointBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a MapPoint instance from a <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static MapPoint CreateMapPoint(MapPointBuilderEx mapPointBuilderEx, SpatialReference spatialReference = null)
```
### CreateMapPoint(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance. The new instance is empty.</p>


```csharp
public static MapPoint CreateMapPoint(SpatialReference spatialReference = null)
```
### CreateMapPoint(double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given X and Y coordinates.</p>


```csharp
public static MapPoint CreateMapPoint(double x, double y, SpatialReference spatialReference = null)
```
### CreateMapPoint(double, double, bool, double, bool, double, bool, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given X and Y coordinates and
other attributes.</p>


```csharp
public static MapPoint CreateMapPoint(double x, double y, bool hasZ, double z, bool hasM, double m, bool hasId, int id, SpatialReference spatialReference = null)
```
### CreateMapPoint(double, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given X, Y, and Z coordinates.
The HasZ property on this instance is set to true.</p>


```csharp
public static MapPoint CreateMapPoint(double x, double y, double z, SpatialReference spatialReference = null)
```
### CreateMapPoint(double, double, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given X, Y, Z and M coordinates.
The HasZ and HasM properties on this instance are set to true.</p>


```csharp
public static MapPoint CreateMapPoint(double x, double y, double z, double m, SpatialReference spatialReference = null)
```
### CreateMapPoint(double, double, double, double, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance with the given X, Y, Z, M and ID coordinates.
The HasZ, HasM and HasID properties on this instance are set to true.</p>


```csharp
public static MapPoint CreateMapPoint(double x, double y, double z, double m, int id, SpatialReference spatialReference = null)
```
### FromEsriShape(byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> from an Esri shape buffer.</p>


```csharp
public static MapPoint FromEsriShape(byte[] esriShapeBuffer, SpatialReference spatialReference = null)
```
### FromGeoCoordinateString(string, SpatialReference, GeoCoordinateType, FromGeoCoordinateMode)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> from a geographic string representation.</p>


```csharp
public static MapPoint FromGeoCoordinateString(string geoCoordString, SpatialReference spatialReference, GeoCoordinateType geoCoordType, FromGeoCoordinateMode geoCoordMode = FromGeoCoordinateMode.Default)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> from a JSON string representation.</p>


```csharp
public static MapPoint FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> from an XML string representation.</p>


```csharp
public static MapPoint FromXml(string xmlString)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Point" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes ID-values also known as ID-awareness.</p>


```csharp
public override bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes M-values also known as M-awareness.</p>


```csharp
public override bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes Z-values also known as Z-awareness.</p>


```csharp
public override bool HasZ { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the ID-coordinate.</p>


```csharp
public int ID { get; set; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Returns true if the point is empty. An empty point has X or Y equal to NaN.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(MapPointBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(MapPointBuilderEx other)
```
### M

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the M-coordinate.</p>


```csharp
public double M { get; set; }
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Sets X and Y to NaN. Sets other attributes to the default values. Does not change the attribute awareness.</p>


```csharp
public override void SetEmpty()
```
### SetValues(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Sets the X and Y coordinates.</p>


```csharp
public void SetValues(double x, double y)
```
### SetValues(double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Sets the X, Y and Z coordinates.</p>


```csharp
public void SetValues(double x, double y, double z)
```
### SetValues(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Sets the X, Y, Z, and M components.</p>


```csharp
public void SetValues(double x, double y, double z, double m)
```
### SetValues(double, double, double, double, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Sets the X, Y, Z, M and ID components.</p>


```csharp
public void SetValues(double x, double y, double z, double m, int id)
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override MapPoint ToGeometry()
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the X coordinate of the point.</p>


```csharp
public double X { get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the Y coordinate of the point.</p>


```csharp
public double Y { get; set; }
```
### Z

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the Z-coordinate.</p>


```csharp
public double Z { get; set; }
```


