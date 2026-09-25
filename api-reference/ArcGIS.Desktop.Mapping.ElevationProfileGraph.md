# ElevationProfileGraph

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Represents an elevation profile graph that is displayed on a mapView.
Use <xref href="ArcGIS.Desktop.Mapping.MapView.GetElevationProfileGraph" data-throw-if-not-resolved="false"></xref> to retrieve the elevation profile graph.
This may return null if no elevation profile graph is visible.
Use one of the MapView.ShowElevationProfileGraph methods to generate a profile graph
along a linear path.  The profile is calculated using the ground elevation surface in the map.</p>


## Object Signature

```csharp
public class ElevationProfileGraph
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Use <xref href="ArcGIS.Desktop.Mapping.MapView.ElevationProfileGraphAdded" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.MapView.ElevationProfileGraphRemoved" data-throw-if-not-resolved="false"></xref>
to determine when the graph is displayed or removed from the mapView.
The profile calculation begins once the graph is displayed.  Use <xref href="ArcGIS.Desktop.Mapping.ElevationProfileGraph.ContentLoaded" data-throw-if-not-resolved="false"></xref>
to determine when the profile calculation has finished.
Once the calculation has been completed, retrieve the elevation profile information using
the <xref href="ArcGIS.Desktop.Mapping.ElevationProfileGraph.Geometry" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.ElevationProfileGraph.ElevationProfileStatistics" data-throw-if-not-resolved="false"></xref> methods.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="10">Elevation profile graphs are temporary and are not saved with the project.<br>
Save the elevation profile information by exporting the profile graph as an image file,
or the elevation profile data in table format or as a row or feature in the geodatabase.</p>


## Members

### CanExport

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Gets if the current elevation profile can be exported. Returns false if the calculation has not yet been completed.</p>


```csharp
public bool CanExport { get; }
```
### Cancel()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Stops the generation of the current elevation profile.</p>


```csharp
public void Cancel()
```
### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Closes the elevation profile graph.</p>


```csharp
public void Close()
```
### ContentLoaded

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Occurs when the elevation profile content of the control has been loaded.</p>


```csharp
public event EventHandler ContentLoaded
```
### ElevationProfileStatistics

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Gets the statistics of the current elevation profile.  Returns null if the calculation has not yet been completed.</p>


```csharp
public ElevationProfileStatistics ElevationProfileStatistics { get; }
```
### ExportToCSV(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Exports the current elevation profile to a CSV file.  Use the <xref href="ArcGIS.Desktop.Mapping.ElevationProfileGraph.CanExport" data-throw-if-not-resolved="false"></xref> function prior to calling this
method to ensure that the elevation profile calculation has completed.</p>


```csharp
public void ExportToCSV(string fileName)
```
### ExportToImage(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Exports the current elevation profile to an image file.</p>


```csharp
public void ExportToImage(string fileName)
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Gets the current elevation profile.  Returns null if the calculation has not yet been completed.</p>


```csharp
public Polyline Geometry { get; }
```
### IsClosed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Gets if the elevation profile graph is closed.</p>


```csharp
public bool IsClosed { get; }
```
### IsExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Gets and sets if the elevation profile graph is expanded.</p>


```csharp
public bool IsExpanded { get; set; }
```
### IsReversed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileGraph.yml" sourcestartlinenumber="1">Gets and sets if the elevation profile on the graph is reversed.</p>


```csharp
public bool IsReversed { get; set; }
```


