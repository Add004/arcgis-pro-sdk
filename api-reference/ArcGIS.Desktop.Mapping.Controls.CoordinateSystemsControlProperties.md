# CoordinateSystemsControlProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Configures the properties to be used to initialize the CoordinateSystemsControl</p>


## Object Signature

```csharp
public class CoordinateSystemsControlProperties
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">To refresh the CoordinateSystemsControl (eg the map's layers change), provide an updated
CoordinateSystemsControlProperties</p>


## Members

### CoordinateSystemsControlProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Construct a CoordinateSystemsControlProperties to configure the CoordinateSystemsControl.
Use the Map, SpatialReference (or Wkid or Wkt), and ShowVerticalCoordinateSystems properties
to configure the control. They are all optional.</p>


```csharp
public CoordinateSystemsControlProperties()
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the map whose layers will be used to populate the 'Layers'
leaf in the CoordinateSystemsControl.</p>


```csharp
public Map Map { get; set; }
```
### ShowVerticalCoordinateSystems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the ShowVerticalCoordinateSystems setting. If this is set to true,
the VerticalCoordinateSystems leaf node is shown in the CoordinateSystemsControl
UI</p>


```csharp
public bool ShowVerticalCoordinateSystems { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the spatial reference to be used to select the SpatialReference in the
CoordinateSystemsControl.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the spatial reference wkid to be used to select the SpatialReference in the
CoordinateSystemsControl.</p>


```csharp
public int Wkid { get; set; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the spatial reference wkt to be used to select the SpatialReference in the
CoordinateSystemsControl.</p>


```csharp
public string Wkt { get; set; }
```


