# IMapDeviceLocationService

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.IMapDeviceLocationService.yml" sourcestartlinenumber="1">Provides required properties and methods for interacting with the active map using
a device location source such as a GPS/GNSS device.</p>


## Object Signature

```csharp
public interface IMapDeviceLocationService
```


## Members

### GetDeviceLocationOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.IMapDeviceLocationService.yml" sourcestartlinenumber="1">Gets the MapDeviceLocationOptions currently used by the MapDeviceLocationService.</p>


```csharp
MapDeviceLocationOptions GetDeviceLocationOptions()
```
### IsDeviceLocationEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.IMapDeviceLocationService.yml" sourcestartlinenumber="1">Gets the enabled state of the current DeviceLocationSource.</p>


```csharp
bool IsDeviceLocationEnabled { get; }
```
### SetDeviceLocationEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.IMapDeviceLocationService.yml" sourcestartlinenumber="1">Enables (or disables) the current DeviceLocationSource. Use <xref href="ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.Open(ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationSource%2cArcGIS.Desktop.Core.DeviceLocation.DeviceLocationProperties)" data-throw-if-not-resolved="false"></xref>
prior to enabling the DeviceLocationSource. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetDeviceLocationEnabled(bool enable)
```
### SetDeviceLocationOptions(MapDeviceLocationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.IMapDeviceLocationService.yml" sourcestartlinenumber="1">Sets a <xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions" data-throw-if-not-resolved="false"></xref> to update the current MapDeviceLocationService settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetDeviceLocationOptions(MapDeviceLocationOptions options)
```
### ZoomOrPanToCurrentLocation(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.IMapDeviceLocationService.yml" sourcestartlinenumber="1">Zooms or pans the active map view to the current location, keeping the current device location at the center.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void ZoomOrPanToCurrentLocation(bool zoom)
```


