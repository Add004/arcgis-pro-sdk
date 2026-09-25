# Coordinate2D

- Type: struct
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">A lightweight structure that holds X and Y values.</p>


## Object Signature

```csharp
[ComVisible(true)]
public struct Coordinate2D : IEquatable<Coordinate2D>
```


## Members

### Coordinate2D(Coordinate3D)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Represents a Coordinate2D with an X and Y value.</p>


```csharp
public Coordinate2D(Coordinate3D coordinate)
```
### Coordinate2D(MapPoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Represents a Coordinate2D with an X and Y value.</p>


```csharp
public Coordinate2D(MapPoint mapPoint)
```
### Coordinate2D(double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Represents a Coordinate2D with an X and Y value.</p>


```csharp
public Coordinate2D(double x, double y)
```
### ConstructEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a new empty Coordinate2D.</p>


```csharp
public static Coordinate2D ConstructEmpty()
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Gets the direction.</p>


```csharp
public double Direction { get; }
```
### Distance(Coordinate2D, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Gets the 2D distance between two instances of Coordinate2D.</p>


```csharp
public static double Distance(Coordinate2D coordinate1, Coordinate2D coordinate2)
```
### DotProduct(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Calculates the dot product of this Coordinate2D and another Coordinate2D.
Vector dot product is used.</p>


```csharp
public double DotProduct(Coordinate2D other)
```
### Equals(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public bool Equals(Coordinate2D other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Obtains a hash code of the object.  Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### GetPerpendicular(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a Coordinate2D that is perpendicular to this vector.</p>


```csharp
public Coordinate2D GetPerpendicular(bool turnRight)
```
### GetUnitVector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a Coordinate2D with Magnitude = 1 from this vector;</p>


```csharp
public Coordinate2D GetUnitVector()
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Indicates if the Coordinate2D is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### Magnitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Gets or sets the length of the Coordinate2D as a vector.</p>


```csharp
public double Magnitude { get; set; }
```
### Midpoint(Coordinate2D, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs the midpoint of the segment connecting two instances of Coordinate2D.</p>


```csharp
public static Coordinate2D Midpoint(Coordinate2D coord1, Coordinate2D coord2)
```
### Move(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Moves the Coordinate2D by adding a shift value to each component.</p>


```csharp
public void Move(double dx, double dy)
```
### Normalize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Normalizes the Coordinate2D which means it is scaled to magnitude = 1.</p>


```csharp
public void Normalize()
```
### QueryComponents()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Gets the components of the Coordinate2D.</p>


```csharp
public Tuple<double, double> QueryComponents()
```
### Rotate(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Rotates the Coordinate2D around the origin.</p>


```csharp
public void Rotate(double angle)
```
### Rotate(double, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Rotates the Coordinate2D around an axis defined by another Coordinate2D.</p>


```csharp
public void Rotate(double angle, Coordinate2D axis)
```
### Scale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Scales the Coordinate2D by the given factor.</p>


```csharp
public void Scale(double scaleFactor)
```
### SetComponents(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Sets the components of the Coordinate2D.</p>


```csharp
public void SetComponents(double x, double y)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Sets the Coordinate2D to empty.</p>


```csharp
public void SetEmpty()
```
### ToMapPoint(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Convert the Coordinate2D into a MapPoint.</p>


```csharp
public MapPoint ToMapPoint(SpatialReference spatialReference = null)
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Gets or sets the X-component.</p>


```csharp
public double X { readonly get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Gets or sets the Y-component.</p>


```csharp
public double Y { readonly get; set; }
```
### operator +(Coordinate2D, Coordinate2D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a new Coordinate2D by adding two Coordinate2D objects.
Vector addition is used.</p>


```csharp
public static Coordinate2D operator +(Coordinate2D a, Coordinate2D b)
```
### operator /(Coordinate2D, double)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a new Coordinate2D by performing scalar division on a Coordinate2D.</p>


```csharp
public static Coordinate2D operator /(Coordinate2D b, double s)
```
### operator ==(Coordinate2D, Coordinate2D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Determines whether the components of the two Coordinate2D objects are equal.</p>


```csharp
public static bool operator ==(Coordinate2D lhs, Coordinate2D rhs)
```
### explicit operator Coordinate2D(MapPoint)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Allow explicit casting of a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> to a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static explicit operator Coordinate2D(MapPoint point)
```
### operator !=(Coordinate2D, Coordinate2D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Determines whether the components of the two Coordinate2D objects are not equal.</p>


```csharp
public static bool operator !=(Coordinate2D lhs, Coordinate2D rhs)
```
### operator *(Coordinate2D, double)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a new Coordinate2D by performing scalar multiplication on a Coordinate2D.</p>


```csharp
public static Coordinate2D operator *(Coordinate2D b, double s)
```
### operator *(double, Coordinate2D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a new Coordinate2D by performing scalar multiplication on a Coordinate2D.</p>


```csharp
public static Coordinate2D operator *(double s, Coordinate2D b)
```
### operator -(Coordinate2D, Coordinate2D)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">Constructs a new Coordinate2D by subtracting two Coordinate2D objects.
Vector subtraction is used.</p>


```csharp
public static Coordinate2D operator -(Coordinate2D a, Coordinate2D b)
```


