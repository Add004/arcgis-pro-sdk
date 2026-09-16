# LineOfSightParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">A class to contain the input values for <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.GetLineOfSight(ArcGIS.Desktop.Mapping.LineOfSightParams)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LineOfSightParams
```


## Members

### LineOfSightParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Default constructor. Initialize a new instance of LineOfSightParams.</p>


```csharp
public LineOfSightParams()
```
### LineOfSightParams(MapPoint, MapPoint, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Constructor overload. Initialize a new instance of LineOfSightParams.</p>


```csharp
public LineOfSightParams(MapPoint observerPoint, MapPoint targetPoint, double observerHeightOffset, double targetHeightOffset, SpatialReference outputSpatialReference)
```
### LineOfSightParams(MapPoint, MapPoint, double, double, bool, bool, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Constructor overload. Initialize a new instance of LineOfSightParams.</p>


```csharp
public LineOfSightParams(MapPoint observerPoint, MapPoint targetPoint, double observerHeightOffset, double targetHeightOffset, bool applyCurvature, bool applyRefraction, double refractionFactor, SpatialReference outputSpatialReference)
```
### LineOfSightParams(Polyline, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Constructor overload. Initialize a new instance of LineOfSightParams.</p>


```csharp
public LineOfSightParams(Polyline sightLine, double observerHeightOffset, double targetHeightOffset, SpatialReference outputSpatialReference)
```
### LineOfSightParams(Polyline, double, double, bool, bool, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Constructor overload. Initialize a new instance of LineOfSightParams.</p>


```csharp
public LineOfSightParams(Polyline sightLine, double observerHeightOffset, double targetHeightOffset, bool applyCurvature, bool applyRefraction, double refractionFactor, SpatialReference outputSpatialReference)
```
### ApplyCurvature

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets whether the earth's curvature should be taken into consideration.  Default value is false.</p>


```csharp
public bool ApplyCurvature { get; set; }
```
### ApplyRefraction

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets whether atmospheric refraction should be taken into consideration.  Default value is false.</p>


```csharp
public bool ApplyRefraction { get; set; }
```
### DefaultRefractionFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets the default refraction factor to apply.  Default value is 0.13.</p>


```csharp
public static double DefaultRefractionFactor { get; }
```
### ObserverHeightOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the vertical offset to apply to the observer point (in the vertical unit of measure of the surface).  Default value is 0.0.</p>


```csharp
public double ObserverHeightOffset { get; set; }
```
### ObserverPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the observer point.</p>


```csharp
public MapPoint ObserverPoint { get; set; }
```
### ObstructionsMultipatchFeatureClass

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the multipatch feature class that defines additional obstructing features.</p>


```csharp
public FeatureClass ObstructionsMultipatchFeatureClass { get; set; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the spatial reference which the output features will be projected to.  Default value is null.
If null, then the output features use the spatial reference of the surface.</p>


```csharp
public SpatialReference OutputSpatialReference { get; set; }
```
### RefractionFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the refraction factor to apply.  Default value is <xref href="ArcGIS.Desktop.Mapping.LineOfSightParams.DefaultRefractionFactor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double RefractionFactor { get; set; }
```
### TargetHeightOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the vertical offset to apply to the target point (in the vertical unit of measure of the surface). Default value is 0.0.</p>


```csharp
public double TargetHeightOffset { get; set; }
```
### TargetPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightParams.yml" sourcestartlinenumber="1">Gets and sets the target point.</p>


```csharp
public MapPoint TargetPoint { get; set; }
```


