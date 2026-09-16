# NMEASnapshot

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Represents a feed off a device location source that conforms to the NMEA specifications.</p>


## Object Signature

```csharp
public sealed class NMEASnapshot : Snapshot
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Refer to
<a href="https://www.trimble.com/OEM_ReceiverHelp/V4.44/en/NMEA-0183messages_MessageOverview.html">NMEA-0183 messages</a></p>


## Members

### Altitude

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the z value or the altitude of the device in meters.</p>


```csharp
public double? Altitude { get; }
```
### AverageSNR

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the average signal to noise ratio.</p>


```csharp
public double? AverageSNR { get; }
```
### CourseOverGround

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the course over ground.</p>


```csharp
public double? CourseOverGround { get; }
```
### DateTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the timestamp of the feed.</p>


```csharp
public DateTime? DateTime { get; }
```
### GGAQualityIndicator

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the GNSS quality indicator.</p>


```csharp
public QualityIndicator? GGAQualityIndicator { get; }
```
### GetPositionAsMapPoint()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Returns the position formatted as a MapPoint from the NMEASnapshot.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override MapPoint GetPositionAsMapPoint()
```
### HDOP

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the horizontal dilution of precision.</p>


```csharp
public double? HDOP { get; }
```
### HorizontalAccuracy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the horizontal accuracy for the current feed.</p>


```csharp
public override double? HorizontalAccuracy { get; }
```
### Latitude

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the latitude.</p>


```csharp
public double? Latitude { get; }
```
### Longitude

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the longitude.</p>


```csharp
public double? Longitude { get; }
```
### MeetsAccuracyThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets if accuracy meets threshold value.</p>


```csharp
public bool? MeetsAccuracyThreshold { get; }
```
### NumSatelliteVehiclesInUse

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the number of satellites in use.</p>


```csharp
public int? NumSatelliteVehiclesInUse { get; }
```
### NumSatelliteVehiclesInView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the number of satellites in the view.</p>


```csharp
public int? NumSatelliteVehiclesInView { get; }
```
### PDOP

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the position dilution of precision.</p>


```csharp
public double? PDOP { get; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref> for the position.</p>


```csharp
public override Coordinate3D? Position { get; }
```
### SatelliteVehicles

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the list of Satellite Vehicles in the view</p>


```csharp
public IList<SatelliteVehicle> SatelliteVehicles { get; }
```
### SpeedOverGround

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the speed the device is moving over the ground in km/h.</p>


```csharp
public double? SpeedOverGround { get; }
```
### VDOP

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the vertical dilution of precision.</p>


```csharp
public double? VDOP { get; }
```
### VerticalAccuracy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.NMEASnapshot.yml" sourcestartlinenumber="1">Gets the vertical accuracy for the current feed.</p>


```csharp
public override double? VerticalAccuracy { get; }
```


