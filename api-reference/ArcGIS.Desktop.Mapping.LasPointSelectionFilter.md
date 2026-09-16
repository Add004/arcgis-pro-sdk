# LasPointSelectionFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="1">Represents the filter used when selecting points in a LAS dataset layer for the purposes of
editing classification codes or classification flags.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="6">See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SelectAsync(ArcGIS.Desktop.Mapping.LasPointSelectionFilter%2cArcGIS.Desktop.Mapping.SelectionCombinationMethod)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LasPointSelectionFilter
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="1">Specify the <xref href="ArcGIS.Desktop.Mapping.LasPointSelectionFilter.FilterGeometry" data-throw-if-not-resolved="false"></xref> to use to search for points.
Set <xref href="ArcGIS.Desktop.Mapping.LasPointSelectionFilter.VisiblePoints" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.LasPointSelectionFilter.ClassCodes" data-throw-if-not-resolved="false"></xref> to add additional criteria to the
filter.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="7">Additional filters are available for specialized selection algorithms; see <xref href="ArcGIS.Desktop.Mapping.LasPointPlaneSelectionFilter" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.LasPointRailSelectionFilter" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### LasPointSelectionFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointSelectionFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointSelectionFilter()
```
### ClassCodes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="1">Gets or sets the list of classification codes to be used in the selection filter.</p>


```csharp
public List<int> ClassCodes { get; set; }
```
### FilterGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the geometry to use for the selection filter.  This must be a non-empty
geometry and should be defined in screen coordinates or in coordinates of the map's spatial reference.</p>


```csharp
public Geometry FilterGeometry { get; set; }
```
### VisiblePoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets whether only visible points are to be used in the selection filter.  Default value is null
indicating don't change the existing visible points setting.</p>


```csharp
public bool? VisiblePoints { get; set; }
```


