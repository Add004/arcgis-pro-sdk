# LasPointPlaneSelectionFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter.yml" sourcestartlinenumber="1">Represents the plane filter used when selecting points in a LAS dataset layer.
The plane filter selects a series of points based on
the original selection until the filter parameters are exceeded.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter.yml" sourcestartlinenumber="7">See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SelectAsync(ArcGIS.Desktop.Mapping.LasPointSelectionFilter%2cArcGIS.Desktop.Mapping.SelectionCombinationMethod)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LasPointPlaneSelectionFilter : LasPointSelectionFilter
```


## Members

### LasPointPlaneSelectionFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointPlaneSelectionFilter()
```
### ClusteringDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the cluster distance in meters.  The default value is 0.2 meters.</p>


```csharp
public double ClusteringDistance { get; set; }
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum distance in meters.  The default value is 6.09 meters.</p>


```csharp
public double MaximumDistance { get; set; }
```
### PlaneTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the plane tolerance value in meters.  The default value is 0.152 meters.</p>


```csharp
public double PlaneTolerance { get; set; }
```


