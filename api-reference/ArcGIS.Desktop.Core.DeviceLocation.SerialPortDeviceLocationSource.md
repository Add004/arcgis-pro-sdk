# SerialPortDeviceLocationSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Represents a location device source such as GPS/GNSS device that is connected via a serial port.</p>


## Object Signature

```csharp
public class SerialPortDeviceLocationSource : DeviceLocationSource, IEquatable<SerialPortDeviceLocationSource>
```


## Members

### SerialPortDeviceLocationSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Creates a SerialPortDeviceLocationSource instance.</p>


```csharp
public SerialPortDeviceLocationSource()
```
### AntennaHeight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Gets and sets antenna height in meters, if your device has one.</p>


```csharp
public double AntennaHeight { get; set; }
```
### BaudRate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Gets and sets BaudRate.</p>


```csharp
public int BaudRate { get; set; }
```
### ComPort

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Gets and sets the COM port which the communication between ArcGIS Pro and a location device such as GPS/GNSS taken place.</p>


```csharp
public string ComPort { get; set; }
```
### DataBits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Gets and set data bits.</p>


```csharp
public int DataBits { get; set; }
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Returns the spatial coordinate system the coordinates will be emitted from a local device such as GPS/GNSS.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override SpatialReference GetSpatialReference()
```
### Parity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Gets and sets data parity.</p>


```csharp
public Parity Parity { get; set; }
```
### SetSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Sets the coordinate system used by GPS/GNSS device.</p>


```csharp
public override void SetSpatialReference(SpatialReference sr)
```
### StopBits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.SerialPortDeviceLocationSource.yml" sourcestartlinenumber="1">Gets and sets stop bits.</p>


```csharp
public StopBits StopBits { get; set; }
```


