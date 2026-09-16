# LasPoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Data.Analyst3D.LasPoint" data-throw-if-not-resolved="false"></xref> represents information about a point in the <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LasPoint : CoreObjectsBase, IDisposable
```


## Members

### ClassCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the class code.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public byte ClassCode { get; }
```
### Coordinate2D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> structure with the X and Y values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D Coordinate2D { get; }
```
### Coordinate3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref> structure with the X, Y, and Z values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D Coordinate3D { get; }
```
### EdgeOfFlightLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the edge of flight line flag of the point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public byte EdgeOfFlightLine { get; }
```
### FileIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the index of the LAS file that the point is found in.  This is 0-based.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FileIndex { get; }
```
### Intensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the intensity of the point.  The intensity is a representation of the pulse return magnitude.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int Intensity { get; }
```
### IsKeyPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets if the point is a key point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsKeyPoint { get; }
```
### IsOverlapPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets if the point is an overlap point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsOverlapPoint { get; }
```
### IsSyntheticPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets if the point is a synthetic point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsSyntheticPoint { get; }
```
### IsWithheld

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets if the point is marked as withheld.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsWithheld { get; }
```
### NearInfraredColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the near infrared color value of this point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int NearInfraredColor { get; }
```
### NumberOfReturns

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the number of returns of the point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public byte NumberOfReturns { get; }
```
### PointID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the point's record number in the LAS file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double PointID { get; }
```
### PointSourceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the source ID of the point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int PointSourceID { get; }
```
### RGBColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.CIM.CIMRGBColor" data-throw-if-not-resolved="false"></xref> representing the red, green and blue components of the point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRGBColor RGBColor { get; }
```
### ReturnNumber

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the return number of the point.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public byte ReturnNumber { get; }
```
### ScanAngleDegree

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the scan angle of this point in degrees.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double ScanAngleDegree { get; }
```
### ScanAngleRank

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the scan angle rank of this point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public short ScanAngleRank { get; }
```
### ScanDirectionFlag

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the scan direction flag of this point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public byte ScanDirectionFlag { get; }
```
### ScannerChannel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the scanner channel of this point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public byte ScannerChannel { get; }
```
### ToMapPoint()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> with the X, Y and Z values.  The spatial reference of the returned point is set to the
spatial reference of the LAS dataset.  See <xref href="ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint ToMapPoint()
```
### UserData

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPoint.yml" sourcestartlinenumber="1">Gets the user data associated with this point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public short UserData { get; }
```


