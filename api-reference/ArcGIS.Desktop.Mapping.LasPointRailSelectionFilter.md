# LasPointRailSelectionFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Represents the rail filter used when selecting points in a LAS dataset layer.
The rail filter selects a series of points along a line based on
the original selection until the filter parameters are exceeded.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="7">See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SelectAsync(ArcGIS.Desktop.Mapping.LasPointSelectionFilter%2cArcGIS.Desktop.Mapping.SelectionCombinationMethod)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LasPointRailSelectionFilter : LasPointSelectionFilter
```


## Members

### LasPointRailSelectionFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointRailSelectionFilter()
```
### MaximumLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum length in meters. This is the longest allowable distance in both directions
along the rail for selection points as rail points. The default value is 200 meters.</p>


```csharp
public double MaximumLength { get; set; }
```
### MaximumOutliers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum allowable number of outliers. If the number of outliers is
below this limit, they are excluded from selection. The default value is 5.</p>


```csharp
public int MaximumOutliers { get; set; }
```
### RailMovingLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the rail moving length in meters. This is the length of the moving window (active
set of points) that continuously moves along the rail after selecting a rail point.
If the value is too small, the selection may go off track. If it is too large, it
will struggle with turns but will perform better when crossing railroad tracks.
The default value is 0.5 meters.</p>


```csharp
public double RailMovingLength { get; set; }
```
### RailThickness

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the rail thickness in meters. This limits the search distance to the left and
right along the rail. The default value is 0.1 meters.</p>


```csharp
public double RailThickness { get; set; }
```
### SearchRadius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the search radius in meters. This is the distance from the moving window's
endpoints within which a point is assessed as a rail point. The default value is 0.25 meters.</p>


```csharp
public double SearchRadius { get; set; }
```
### VerticalThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the vertical threshold in meters. This is the minimum above-ground distance for a
point to be considered a rail point. The default value is 0.05 meters.</p>


```csharp
public double VerticalThreshold { get; set; }
```
### VerticalTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the vertical tolerance in meters. This is the allowable variation in the Z dimension
to determine whether a point is a rail point and will be included in the selection.
The default value is 0.02 meters.</p>


```csharp
public double VerticalTolerance { get; set; }
```


