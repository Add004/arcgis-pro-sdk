# SpatialReferenceBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Builder for creating a <xref href="ArcGIS.Core.Geometry.SpatialReference?text=SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SpatialReferenceBuilder : CoreObjectsBase, IDisposable
```


## Members

### SpatialReferenceBuilder(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(SpatialReference spatialReference)
```
### SpatialReferenceBuilder(int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(int wkid)
```
### SpatialReferenceBuilder(int, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(int wkid, int vcsWkid)
```
### SpatialReferenceBuilder(int, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(int wkid, string vcsWkt)
```
### SpatialReferenceBuilder(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(string wkt)
```
### SpatialReferenceBuilder(string, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(string wkt, int vcsWkid)
```
### SpatialReferenceBuilder(string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of the SpatialReferenceBuilder class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder(string wkt, string vcsWkt)
```
### BaseGeographic

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the base geographic coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference BaseGeographic { get; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Returns a clone of the builder. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReferenceBuilder Clone()
```
### CreateSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(SpatialReference spatialReference)
```
### CreateSpatialReference(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(int wkid)
```
### CreateSpatialReference(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(int wkid, int vcsWkid)
```
### CreateSpatialReference(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(int wkid, string vcsWkt)
```
### CreateSpatialReference(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(string wkt)
```
### CreateSpatialReference(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(string wkt, int vcsWkid)
```
### CreateSpatialReference(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static SpatialReference CreateSpatialReference(string wkt, string vcsWkt)
```
### CreateWgs84UtmFromLocation(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a WGS84 UTM zone spatial reference</p>


```csharp
public static SpatialReference CreateWgs84UtmFromLocation(double longitude, double latitude)
```
### Domain

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the valid extent of this coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope Domain { get; set; }
```
### FalseM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the False M value. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double FalseM { get; set; }
```
### FalseX

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the False X value. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double FalseX { get; set; }
```
### FalseY

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the False Y value. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double FalseY { get; set; }
```
### FalseZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the False Z value. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double FalseZ { get; set; }
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class from a JSON string representation.</p>


```csharp
public static SpatialReference FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> class from an XML string representation.</p>


```csharp
public static SpatialReference FromXml(string xmlString)
```
### GetWkt2(WktFormatMode)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the well-known text (2) for this instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetWkt2(WktFormatMode wktFormatMode)
```
### IsGeographic

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets a value indicating if this is a geographic coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsGeographic { get; }
```
### IsImage

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets a value indicating if this is an image coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsImage { get; }
```
### IsPannable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets a value indicating if this spatial reference is pannable. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsPannable { get; }
```
### IsProjected

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets a value indicating if this is a projected coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsProjected { get; }
```
### IsUnknown

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets a value indicating if this is the Unknown coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsUnknown { get; }
```
### MScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the M Scale. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double MScale { get; set; }
```
### MTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the M Tolerance.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double MTolerance { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the name for this instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Name { get; }
```
### PositiveDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the positive direction of the vertical coordinate system. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PositiveDirection PositiveDirection { get; }
```
### SetDefaultMTolerance()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Sets the default MTolerance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultMTolerance()
```
### SetDefaultXYResolution()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Sets the default XYResolution. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultXYResolution()
```
### SetDefaultXYTolerance()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Sets the default XYTolerance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultXYTolerance()
```
### SetDefaultZTolerance()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Sets the default ZTolerance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultZTolerance()
```
### ToSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference ToSpatialReference()
```
### Unit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the units that the spatial reference coordinates are in. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Unit Unit { get; set; }
```
### VcsWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the vertical coordinate system well-known ID. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int VcsWkid { get; set; }
```
### VcsWkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the vertical coordinate system well-known text. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string VcsWkt { get; set; }
```
### VerticalShift

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the vertical shift of the vertical coordinate system.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double VerticalShift { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the well-known ID for this instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int Wkid { get; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets the well-known text for this instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Wkt { get; }
```
### XYResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the XYResolution. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double XYResolution { get; set; }
```
### XYScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the XY Scale. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double XYScale { get; set; }
```
### XYTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the XYTolerance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double XYTolerance { get; set; }
```
### ZScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the Z Scale. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double ZScale { get; set; }
```
### ZTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the Z Tolerance.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double ZTolerance { get; set; }
```
### ZUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Gets or sets the units that the spatial reference Z-coordinates are in. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Unit ZUnit { get; set; }
```


