# DeviceLocationService

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Represents the device location service for connecting to GPS/GNSS devices.</p>


## Object Signature

```csharp
public sealed class DeviceLocationService : IDeviceLocationService
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">There can only be one device location source open at any one time.<br><p>You cannot create a DeviceLocationService instance. Instead use the <xref href="ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.Instance" data-throw-if-not-resolved="false"></xref>
property to access the singleton DeviceLocationService instance which will have been already created.</p><p>Subscribe to <xref href="ArcGIS.Desktop.Core.DeviceLocation.Events.SnapshotChangedEvent" data-throw-if-not-resolved="false"></xref> event to receive
coordinates and metadata from the open device location source <xref href="ArcGIS.Desktop.Core.DeviceLocation.Snapshot" data-throw-if-not-resolved="false"></xref>.</p><p>
To interact with the current or active map view using the device location,
use the <xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService" data-throw-if-not-resolved="false"></xref> instance.</p>
<p>
Subscribe to the <xref href="ArcGIS.Desktop.Core.DeviceLocation.Events.DeviceLocationSourceChangedEvent" data-throw-if-not-resolved="false"></xref> to receive notifications
when the current device location source is changed.
</p>


## Members

### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Closes the current device location source connection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Close()
```
### GetCurrentSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Returns the most recent snapshot received from the open device location source.</p>


```csharp
public Snapshot GetCurrentSnapshot()
```
### GetProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationProperties" data-throw-if-not-resolved="false"></xref> in use.</p>


```csharp
public DeviceLocationProperties GetProperties()
```
### GetSource()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Returns the device location source currently in use.</p>


```csharp
public DeviceLocationSource GetSource()
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Returns the singleton IDeviceLocationService instance.</p>


```csharp
public static IDeviceLocationService Instance { get; }
```
### IsDeviceConnected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Returns the connection status of the selected location source.</p>


```csharp
public bool IsDeviceConnected()
```
### IsLogging

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Gets whether logging is in progress</p>


```csharp
public bool IsLogging { get; }
```
### Open(DeviceLocationSource, DeviceLocationProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Connects to a new device location source such as a GPS/GNSS device via a COM port.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Open(DeviceLocationSource source, DeviceLocationProperties props = null)
```
### UpdateProperties(DeviceLocationProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Updates properties on the current device location source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateProperties(DeviceLocationProperties props)
```
### UpdateSource(DeviceLocationSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationService.yml" sourcestartlinenumber="1">Updates to a new device location source, such as a GPS/GNSS device, via a COM port.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateSource(DeviceLocationSource source)
```


