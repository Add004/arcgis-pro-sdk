# ElevationProfileParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileParameters.yml" sourcestartlinenumber="1">Encapsulates a set of properties used in the generation of an elevation profile.  Use with MapView.ShowElevationProfileGraph.</p>


## Object Signature

```csharp
public class ElevationProfileParameters
```


## Members

### ElevationProfileParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileParameters.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
public ElevationProfileParameters()
```
### Densify

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileParameters.yml" sourcestartlinenumber="1">Gets and sets whether the elevation profile should be densified when generated. Default value is true.</p>


```csharp
public bool Densify { get; set; }
```
### DistanceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileParameters.yml" sourcestartlinenumber="1">Gets and sets the distance unit used for the elevation profile values and statistics.    Default value is null.
If null is specified, then the current value in the Elevation Profile dock pane is used.</p>


```csharp
public DisplayUnitFormat DistanceUnit { get; set; }
```
### SurfaceLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileParameters.yml" sourcestartlinenumber="1">Gets and sets the elevation surface layer used to obtain the elevation values. Default value is null.
If null is specified, then the default Ground Surface will be used.</p>


```csharp
public ElevationSurfaceLayer SurfaceLayer { get; set; }
```


