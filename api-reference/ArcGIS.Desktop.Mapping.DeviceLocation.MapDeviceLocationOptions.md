# MapDeviceLocationOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.DeviceLocation.html">DeviceLocation</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Represents the settings available for configuring the
<xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationService" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapDeviceLocationOptions
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Use the MapDeviceLocationOptions to update the current device location source with
new options</p>


## Members

### MapDeviceLocationOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Create a new MapDeviceLocationOptions instance.</p>


```csharp
public MapDeviceLocationOptions()
```
### DeviceLocationVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Gets and sets the the device location visibility on the map view.</p>


```csharp
public bool DeviceLocationVisibility { get; set; }
```
### NavigationMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Gets and sets the current <xref href="ArcGIS.Desktop.Mapping.DeviceLocation.MappingDeviceLocationNavigationMode" data-throw-if-not-resolved="false"></xref> for the active map view.</p>


```csharp
public MappingDeviceLocationNavigationMode NavigationMode { get; set; }
```
### ShowAccuracyBuffer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Gets and sets whether to show accuracy buffer on the map.</p>


```csharp
public bool ShowAccuracyBuffer { get; set; }
```
### TrackUpNavigation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DeviceLocation.MapDeviceLocationOptions.yml" sourcestartlinenumber="1">Gets and sets whether the heading of the location from the device points to the top of the screen.</p>


```csharp
public bool TrackUpNavigation { get; set; }
```


