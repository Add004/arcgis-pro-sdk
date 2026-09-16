# Coordinate3D

- Type: struct
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">A structure containing methods to manipulate 3D vertices and 3D vectors.</p>


## Object Signature

```csharp
[ComVisible(true)]
public struct Coordinate3D : IEquatable<Coordinate3D>
```


## Members

### Coordinate3D(Coordinate3D)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a Coordinate3D with an X, Y, and Z value used for manipulating 3D vertices and 3D vectors.</p>


```csharp
public Coordinate3D(Coordinate3D coordinate)
```
### Coordinate3D(MapPoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a Coordinate3D with an X, Y, and Z value used for manipulating 3D vertices and 3D vectors.</p>


```csharp
public Coordinate3D(MapPoint mapPoint)
```
### Coordinate3D(double, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a Coordinate3D with an X, Y, and Z value used for manipulating 3D vertices and 3D vectors.</p>


```csharp
public Coordinate3D(double x, double y, double z)
```
### AddCoordinate3D(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a new Coordinate3D by adding another Coordinate3D to this Coordinate3D.
Vector addition is used.</p>


```csharp
public Coordinate3D AddCoordinate3D(Coordinate3D other)
```
### Azimuth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets the azimuth of the Coordinate3D. The azimuth is measured in radians.</p>


```csharp
public double Azimuth { get; }
```
### CrossProduct(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs the cross product of this Coordinate3D and another Coordinate3D.
Vector cross product is used.</p>


```csharp
public Coordinate3D CrossProduct(Coordinate3D other)
```
### Distance(Coordinate3D, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets the 3D distance between two instances of Coordinate3D.</p>


```csharp
public static double Distance(Coordinate3D coordinate1, Coordinate3D coordinate2)
```
### DotProduct(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Calculates the dot product of this Coordinate3D and another Coordinate3D.
Vector dot product is used.</p>


```csharp
public double DotProduct(Coordinate3D other)
```
### Equals(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public bool Equals(Coordinate3D other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Obtains a hash code of the object.  Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### GetUnitVector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a Coordinate3D with Magnitude = 1 from this vector;</p>


```csharp
public Coordinate3D GetUnitVector()
```
### Inclination

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets the inclination of the Coordinate3D. The inclination is measured in radians.</p>


```csharp
public double Inclination { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Indicates if the Coordinate3D is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### Magnitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets or sets the length of the Coordinate3D as a vector.</p>


```csharp
public double Magnitude { get; set; }
```
### Move(double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Moves the Coordinate3D by adding a shift value to each component.</p>


```csharp
public void Move(double dx, double dy, double dz)
```
### Normalize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Normalizes the Coordinate3D which means it is scaled to magnitude = 1.</p>


```csharp
public void Normalize()
```
### QueryComponents()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets the components of the Coordinate3D.</p>


```csharp
public Tuple<double, double, double> QueryComponents()
```
### QueryPolarComponents()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets the polar components of the Coordinate3D. Angles are in radians.</p>


```csharp
public Tuple<double, double, double> QueryPolarComponents()
```
### Rotate(double, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Rotates the Coordinate3D around an axis defined by another Coordinate3D. The angle is in radians.</p>


```csharp
public void Rotate(double angle, Coordinate3D axis)
```
### Scale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Scales the Coordinate3D by the given factor.</p>


```csharp
public void Scale(double scaleFactor)
```
### SetComponents(double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Sets the components of the Coordinate3D.</p>


```csharp
public void SetComponents(double x, double y, double z)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Sets the Coordinate3D to empty.</p>


```csharp
public void SetEmpty()
```
### SetPolarComponents(double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Sets the components of the Coordinate3D from polar components. Angles are in radians.</p>


```csharp
public void SetPolarComponents(double azimuth, double inclination, double magnitude)
```
### ToMapPoint(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Convert the Coordinate3D into a MapPoint.</p>


```csharp
public MapPoint ToMapPoint(SpatialReference spatialReference = null)
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets or sets the X-component.</p>


```csharp
public double X { readonly get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets or sets the Y-component.</p>


```csharp
public double Y { readonly get; set; }
```
### Z

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Gets or sets the Z-component.</p>


```csharp
public double Z { readonly get; set; }
```
### operator +(Coordinate3D, Coordinate3D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a new Coordinate3D by adding two Coordinate3D objects.
Vector addition is used.</p>


```csharp
public static Coordinate3D operator +(Coordinate3D a, Coordinate3D b)
```
### operator ==(Coordinate3D, Coordinate3D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Determines whether the components of the two Coordinate3D objects are equal.</p>


```csharp
public static bool operator ==(Coordinate3D lhs, Coordinate3D rhs)
```
### explicit operator Coordinate3D(MapPoint)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Allow explicit casting of a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> to a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static explicit operator Coordinate3D(MapPoint point)
```
### operator !=(Coordinate3D, Coordinate3D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Determines whether the components of the two Coordinate3D objects are not equal.</p>


```csharp
public static bool operator !=(Coordinate3D lhs, Coordinate3D rhs)
```
### operator *(double, Coordinate3D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a new Coordinate3D by performing scalar multiplication on a Coordinate3D.</p>


```csharp
public static Coordinate3D operator *(double s, Coordinate3D b)
```
### operator -(Coordinate3D, Coordinate3D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">Constructs a new Coordinate3D by subtracting two Coordinate3D objects.</p>


```csharp
public static Coordinate3D operator -(Coordinate3D a, Coordinate3D b)
```


