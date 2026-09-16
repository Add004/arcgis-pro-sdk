# FrameworkExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend ArcGIS.Desktop.Framework members.</p>


## Object Signature

```csharp
public static class FrameworkExtender
```


## Members

### CanOpenTablePane(PaneCollection, MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Determines if the mapMember can be opened by the table pane.</p>


```csharp
public static bool CanOpenTablePane(this PaneCollection paneCollection, MapMember mapMember)
```
### CreateMapPaneAsync(PaneCollection, CIMMapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new map pane which is a container for a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<IMapPane> CreateMapPaneAsync(this PaneCollection paneCollection, CIMMapView mapView)
```
### CreateMapPaneAsync(PaneCollection, Map, Envelope, MapViewingMode?, TimeRange)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new map pane which is a container for a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<IMapPane> CreateMapPaneAsync(this PaneCollection paneCollection, Map map, Envelope extent, MapViewingMode? viewingMode = null, TimeRange timeExtent = null)
```
### CreateMapPaneAsync(PaneCollection, Map, Bookmark, MapViewingMode?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new map pane which is a container for a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<IMapPane> CreateMapPaneAsync(this PaneCollection paneCollection, Map map, Bookmark bookmark, MapViewingMode? viewingMode = null)
```
### CreateMapPaneAsync(PaneCollection, Map, Camera, MapViewingMode?, TimeRange)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new map pane which is a container for a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<IMapPane> CreateMapPaneAsync(this PaneCollection paneCollection, Map map, Camera camera, MapViewingMode? viewingMode = null, TimeRange timeExtent = null)
```
### CreateMapPaneAsync(PaneCollection, Map, MapViewingMode?, TimeRange)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new map pane which is a container for a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<IMapPane> CreateMapPaneAsync(this PaneCollection paneCollection, Map map, MapViewingMode? viewingMode = null, TimeRange timeExtent = null)
```
### GetLinkChartMaps(PaneCollection, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Gets the list of maps that are link charts that contain the specified knowledge graph service.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Map> GetLinkChartMaps(this PaneCollection paneCollection, string kgServiceUri)
```
### GetMapTableView(PaneCollection, MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Gets or creates the CIMMapTableView for a MapMember. If the table pane has been opened for this MapMember, it will initialize the
CIMMapTableView with the pane values.
If a table pane has never been opened, it will initialize the CIMMapTableView with the default table pane values.</p>


```csharp
public static CIMMapTableView GetMapTableView(this PaneCollection paneCollection, MapMember mapMember)
```
### OpenTablePane(PaneCollection, CIMMapTableView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Opens a table pane for a MapMember. If a table pane is already open it will be activated.
You must be on the UI thread to call this function.</p>


```csharp
public static ITablePane OpenTablePane(this PaneCollection paneCollection, CIMMapTableView mapTableView)
```
### OpenTablePane(PaneCollection, MapMember, TableViewMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.FrameworkExtender.yml" sourcestartlinenumber="1">Opens a table pane for a MapMember. If a table pane is already open it will be activated.
You must be on the UI thread to call this function.</p>


```csharp
public static ITablePane OpenTablePane(this PaneCollection paneCollection, MapMember mapMember, TableViewMode viewMode = TableViewMode.eAllRecords)
```


