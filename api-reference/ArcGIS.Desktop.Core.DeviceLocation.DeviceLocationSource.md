# DeviceLocationSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationSource.yml" sourcestartlinenumber="1">Represents a location device source such as GPS/GNSS device.</p>


## Object Signature

```csharp
public class DeviceLocationSource : PropertyChangedBase
```


## Members

### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationSource.yml" sourcestartlinenumber="1">Returns the spatial coordinate system the coordinates will be emitted from a local device such as GPS/GNSS.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual SpatialReference GetSpatialReference()
```
### SetSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationSource.yml" sourcestartlinenumber="1">Sets the coordinate system used by GPS/GNSS device.</p>


```csharp
public virtual void SetSpatialReference(SpatialReference sr)
```


