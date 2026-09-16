# LasPointElevationRangeFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Filter for display of points in a LAS dataset layer.  See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.GetElevationRangeFilter" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SetElevationRangeFilter(ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LasPointElevationRangeFilter
```


## Members

### LasPointElevationRangeFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Constructs a default instance of <xref href="ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointElevationRangeFilter()
```
### LasPointElevationRangeFilter(bool, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Constructs an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointElevationRangeFilter(bool isEnabled, double minZ, double maxZ)
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Gets and sets the enabled flag.  Default value is false.</p>


```csharp
public bool IsEnabled { get; set; }
```
### MaxZ

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum elevation value in meters.  Default value is <xref href="System.Double.MaxValue" data-throw-if-not-resolved="false"></xref>;</p>


```csharp
public double MaxZ { get; set; }
```
### MinZ

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Gets and sets the minimum elavation value in meters.  Default value is <xref href="System.Double.MinValue" data-throw-if-not-resolved="false"></xref>;</p>


```csharp
public double MinZ { get; set; }
```
### ResetRange()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointElevationRangeFilter.yml" sourcestartlinenumber="1">Resets the minimum and maximum values. The minimum value is set to <xref href="System.Double.MinValue" data-throw-if-not-resolved="false"></xref>.  The maximum value is set to <xref href="System.Double.MaxValue" data-throw-if-not-resolved="false"></xref>;</p>


```csharp
public void ResetRange()
```


