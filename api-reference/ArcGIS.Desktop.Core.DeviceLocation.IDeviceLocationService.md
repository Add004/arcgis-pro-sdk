# IDeviceLocationService

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Provides required properties and methods to open and close a connection
to a location device such as a GPS/GNSS device.</p>


## Object Signature

```csharp
public interface IDeviceLocationService
```


## Members

### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Closes the current device location connection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void Close()
```
### GetCurrentSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Returns the most recent snapshot received from a GNNS/GPS device.</p>


```csharp
Snapshot GetCurrentSnapshot()
```
### GetProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Desktop.Core.DeviceLocation.DeviceLocationProperties" data-throw-if-not-resolved="false"></xref> being used.</p>


```csharp
DeviceLocationProperties GetProperties()
```
### GetSource()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Returns the device location source currently being used.</p>


```csharp
DeviceLocationSource GetSource()
```
### IsDeviceConnected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Returns the connection status of the selected location source.</p>


```csharp
bool IsDeviceConnected()
```
### Open(DeviceLocationSource, DeviceLocationProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Connects to a new device location source, such as a GPS/GNSS device, via a COM port.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void Open(DeviceLocationSource source, DeviceLocationProperties props = null)
```
### UpdateProperties(DeviceLocationProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Updates properties on the current device location source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void UpdateProperties(DeviceLocationProperties props)
```
### UpdateSource(DeviceLocationSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.IDeviceLocationService.yml" sourcestartlinenumber="1">Updates to a new device location source, such as a GPS/GNSS device, via a COM port.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void UpdateSource(DeviceLocationSource source)
```


