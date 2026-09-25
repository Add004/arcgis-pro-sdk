# VerticalCoordinateSystem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Represents a vertical coordinate system and provides access to its definition and properties.
A vertical coordinate system defines the origin used for height or depth values.</p>


## Object Signature

```csharp
public class VerticalCoordinateSystem
```


## Members

### Create(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Creates a vertical coordinate system from a well-known ID.</p>


```csharp
public static VerticalCoordinateSystem Create(int wkid)
```
### Create(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Creates a vertical coordinate system from a well-known text definition.</p>


```csharp
public static VerticalCoordinateSystem Create(string wkt)
```
### Datum

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the datum associated with the vertical coordinate system.
The datum in an ellipsoidal VCS or vertical datum in a gravity-related VCS,
is the reference point for elevation values.</p>


```csharp
public Datum Datum { get; }
```
### GetWkt2(WktFormatMode)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Returns the WKT2 representation of the vertical coordinate system.</p>


```csharp
public string GetWkt2(WktFormatMode formatMode)
```
### LinearUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the linear unit used by the vertical coordinate system.
The linear unit defines the unit of measurement for z-values, generally in meters or feet.</p>


```csharp
public LinearUnit LinearUnit { get; }
```
### PositiveDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the positive direction of the vertical axis.
The positive direction determines if z-values represent height or depth.</p>


```csharp
public PositiveDirection PositiveDirection { get; }
```
### VcsType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the type of the vertical coordinate system.</p>


```csharp
public VcsType VcsType { get; }
```
### VerticalShift

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the vertical shift applied by the vertical coordinate system.
The vertical shift sets a built-in vertical offset automatically adding or subtracting from each z-value.</p>


```csharp
public double VerticalShift { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the well-known ID of the vertical coordinate system.</p>


```csharp
public int Wkid { get; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Gets the well-known text representation of the vertical coordinate system.</p>


```csharp
public string Wkt { get; }
```


