# Snapshot

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Snapshot.yml" sourcestartlinenumber="1">Represents a device location source feed.</p>


## Object Signature

```csharp
public abstract class Snapshot
```


## Members

### Snapshot()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Snapshot.yml" sourcestartlinenumber="1">Represents a device location source feed.</p>


```csharp
protected Snapshot()
```
### GetPositionAsMapPoint()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Snapshot.yml" sourcestartlinenumber="1">Returns a point geometry of MapPoint type from the Snapshot.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public abstract MapPoint GetPositionAsMapPoint()
```
### HorizontalAccuracy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Snapshot.yml" sourcestartlinenumber="1">Gets the horizontal accuracy for the current feed.</p>


```csharp
public abstract double? HorizontalAccuracy { get; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Snapshot.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public abstract Coordinate3D? Position { get; }
```
### VerticalAccuracy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Snapshot.yml" sourcestartlinenumber="1">Gets the vertical accuracy for the current feed.</p>


```csharp
public abstract double? VerticalAccuracy { get; }
```


