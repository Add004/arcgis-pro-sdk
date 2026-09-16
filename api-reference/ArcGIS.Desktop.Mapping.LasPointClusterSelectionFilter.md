# LasPointClusterSelectionFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter.yml" sourcestartlinenumber="1">Represents the cluster filter used when selecting points in a LAS dataset layer.
The cluster filter adds additional points to the selection that surround
the original selection until the filter parameters are exceeded.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter.yml" sourcestartlinenumber="7">See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SelectAsync(ArcGIS.Desktop.Mapping.LasPointSelectionFilter%2cArcGIS.Desktop.Mapping.SelectionCombinationMethod)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LasPointClusterSelectionFilter : LasPointSelectionFilter
```


## Members

### LasPointClusterSelectionFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointClusterSelectionFilter()
```
### MaximumNumberOfPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum number of points to be included in the selection. The default value is 1000.</p>


```csharp
public int MaximumNumberOfPoints { get; set; }
```
### SearchRadius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClusterSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the search radius in meters. The default value is 0.2 meters.</p>


```csharp
public double SearchRadius { get; set; }
```


