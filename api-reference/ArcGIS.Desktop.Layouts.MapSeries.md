# MapSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Represents a map series that may be associated with a layout.</p>


## Object Signature

```csharp
public abstract class MapSeries
```

## Remarks

<p>
    You can create multiple map series but a layout can only have one associated map series at a time.  There are two basic ways you can work with a map series.
    </p>
<p>
    First, you can reference the layout's currently active map series using the <xref href="ArcGIS.Desktop.Layouts.Layout.MapSeries?text=MapSeries" data-throw-if-not-resolved="false"></xref> property
    on the <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>. This returns a map series CIM definition.  Changes can be made and then pushed back 
    to the Layout using the <xref href="ArcGIS.Desktop.Layouts.Layout.SetMapSeries?text=SetMapSeries()" data-throw-if-not-resolved="false"></xref> method.
    </p>
<p>
    Second, you can create a new map series using a constructor like <xref href="ArcGIS.Desktop.Layouts.MapSeries.CreateSpatialMapSeries?text=CreateSpatialMapSeries" data-throw-if-not-resolved="false"></xref>.
    This will also return a CIM definition that can be modified and pushed back to the Layout using the
    <xref href="ArcGIS.Desktop.Layouts.Layout.SetMapSeries?text=SetMapSeries()" data-throw-if-not-resolved="false"></xref> method.
    </p>
<p> To export a map series you need to contruct an <xref href="ArcGIS.Desktop.Mapping.ExportFormat?text=ExportFormat" data-throw-if-not-resolved="false"></xref> 
    and a <xref href="ArcGIS.Desktop.Layouts.MapSeriesExportOptions?text=MapSeriesExportOptions" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### CreateBookmarkMapSeries(Layout, MapFrame)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Creates a bookmark map series. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public static BookmarkMapSeries CreateBookmarkMapSeries(Layout layout, MapFrame mapFrame)
```
### CreateSpatialMapSeries(Layout, MapFrame, BasicFeatureLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Creates a spatial map series. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public static SpatialMapSeries CreateSpatialMapSeries(Layout layout, MapFrame mapFrame = null, BasicFeatureLayer indexLayer = null, string nameField = null)
```
### CreateThematicMapSeries(Layout, MapFrame)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Creates a thematic map series. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public static ThematicMapSeries CreateThematicMapSeries(Layout layout, MapFrame mapFrame)
```
### CurrentPageName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the current map series page name.</p>


```csharp
public string CurrentPageName { get; }
```
### CurrentPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the current map series page number.</p>


```csharp
public string CurrentPageNumber { get; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets and sets the map series enabled state.</p>


```csharp
public bool Enabled { get; set; }
```
### FindPageNumber(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Returns a map series page number based on the name field value of the index feature.</p>


```csharp
public string FindPageNumber(string pageName)
```
### FirstPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the first page number of the map series.</p>


```csharp
public string FirstPageNumber { get; }
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the CIM definition of the map series.</p>


```csharp
public CIMMapSeries GetDefinition()
```
### LastPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the last page number of the map series.</p>


```csharp
public string LastPageNumber { get; }
```
### MapFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets and sets the associated <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapFrame MapFrame { get; set; }
```
### NextPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the next page number relative to the current map series page number.</p>


```csharp
public string NextPageNumber { get; }
```
### PageCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the number of pages in the map series.</p>


```csharp
public int PageCount { get; }
```
### PreviousPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets the previous page number relative to the current map series page number.</p>


```csharp
public string PreviousPageNumber { get; }
```
### SetCurrentPageNumber(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Sets the current map series page number. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCurrentPageNumber(string pageNumber)
```
### SetDefinition(CIMMapSeries)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Sets the CIM definition of the map series. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMMapSeries cimMapSeries)
```
### StartingPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeries.yml" sourcestartlinenumber="1">Gets and sets the starting map series page number.</p>


```csharp
public int StartingPageNumber { get; set; }
```


