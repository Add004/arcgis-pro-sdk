# MappingDeviceLocationNavigationMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MappingDeviceLocationNavigationMode.yml" sourcestartlinenumber="1">Specifies how the current map view is repositioned using the
open device source location (i.e via GPS/GNSS).</p>


## Object Signature

```csharp
public enum MappingDeviceLocationNavigationMode
```


## Members

### KeepAtCenter

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MappingDeviceLocationNavigationMode.yml" sourcestartlinenumber="1">Keep map view centered at the device location.</p>


```csharp
KeepAtCenter = 1
```
### KeepWithinView

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MappingDeviceLocationNavigationMode.yml" sourcestartlinenumber="1">Center map view at the device location only when the device location goes outside of
the current extent.</p>


```csharp
KeepWithinView = 2
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MappingDeviceLocationNavigationMode.yml" sourcestartlinenumber="1">Map view's extent does not get changed automatically.</p>


```csharp
None = 0
```


