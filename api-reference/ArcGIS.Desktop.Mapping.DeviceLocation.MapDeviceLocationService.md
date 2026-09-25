# MapDeviceLocationService

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">The Map Device Location Service will interact with the active map using the current open device location
source, such as a GPS/GNSS device.</p>


## Object Signature

```csharp
public class MapDeviceLocationService : IMapDeviceLocationService
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">The MapDeviceLocationService is a singleton. To access the service use its
<xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.Instance" data-throw-if-not-resolved="false"></xref> property.
Once connected, the service allows you to zoom or pan to the current location received from your device.
Use the service to show/hide the location, adjust the accuracy buffer on the map, interactively
Zoom or pan the current map view, and adjust how the map view responds to the current device location.
The map view can either be kept centered on the location or rotated to &quot;track&quot; the location always keeping the
location heading orientated to the top of the screen. Refer to
<xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.SetDeviceLocationOptions(ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions)" data-throw-if-not-resolved="false"></xref><p>To connect to a location device refer to
<xref href="ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.Open(ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationSource%2cArcGIS.Desktop.Core.DeviceLocation.DeviceLocationProperties)" data-throw-if-not-resolved="false"></xref></p>


## Members

### GetDeviceLocationOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">Gets the MapDeviceLocationOptions currently used by the MapDeviceLocationService.</p>


```csharp
public MapDeviceLocationOptions GetDeviceLocationOptions()
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">Gets the singleton IMapDeviceLocationService instance.</p>


```csharp
public static IMapDeviceLocationService Instance { get; }
```
### IsDeviceLocationEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">Determines the enabled state of the current DeviceLocationSource.</p>


```csharp
public bool IsDeviceLocationEnabled { get; }
```
### SetDeviceLocationEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">Enables (or disables) the current DeviceLocationSource. Use <xref href="ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.Open(ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationSource%2cArcGIS.Desktop.Core.DeviceLocation.DeviceLocationProperties)" data-throw-if-not-resolved="false"></xref>
prior to enabling the DeviceLocationSource. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDeviceLocationEnabled(bool enable)
```
### SetDeviceLocationOptions(MapDeviceLocationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">Sets a <xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions" data-throw-if-not-resolved="false"></xref> to update
the current MapDeviceLocationService settings. This method must be called on the MCT. Use QueuedTask.Run.
Use QueuedTask.Run.</p>


```csharp
public void SetDeviceLocationOptions(MapDeviceLocationOptions options)
```
### ZoomOrPanToCurrentLocation(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService.yml" sourcestartlinenumber="1">Zooms or pans the active map view to the current location, keeping the current device location at the center.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ZoomOrPanToCurrentLocation(bool zoom)
```


