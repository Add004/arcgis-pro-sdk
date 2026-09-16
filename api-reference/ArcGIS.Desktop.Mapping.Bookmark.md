# Bookmark

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Represents a geographic location in the map. This location can also contain a specific point in time.</p>


## Object Signature

```csharp
public sealed class Bookmark : PropertyChangedBase
```

## Remarks

<p>Bookmarks can be spatial (2D or 3D) and temporal. If your map is time-enabled, bookmarks can be created for a specific point in time. Bookmarks in an
    ArcGIS Pro project are associated and managed with the map they were created in. Bookmarks are transferable, so you can re-use bookmarks between multiple maps
    and scenes in your project, as well as with or without temporal information.</p>
<p>You can call the <xref href="ArcGIS.Desktop.Mapping.Map.GetBookmarks" data-throw-if-not-resolved="false"></xref> method on the <xref href="ArcGIS.Desktop.Mapping.Map" data-throw-if-not-resolved="false"></xref> to return a collection of bookmarks for the map. An similar extension
    method, <xref href="ArcGIS.Desktop.Core.ProjectExtender.GetBookmarks(ArcGIS.Desktop.Core.Project)" data-throw-if-not-resolved="false"></xref>, is available off of Project which will return all the bookmarks in the Project. You can use the bookmark to navigate the view by calling the
    <xref href="ArcGIS.Desktop.Mapping.MapView.ZoomTo(ArcGIS.Desktop.Mapping.Bookmark%2cSystem.Nullable%7bSystem.TimeSpan%7d)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Mapping.MapView.PanTo(ArcGIS.Desktop.Mapping.Bookmark%2cSystem.Nullable%7bSystem.TimeSpan%7d)" data-throw-if-not-resolved="false"></xref> methods on the <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets the description of the bookmark.</p>


```csharp
public string Description { get; }
```
### FolderName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets the folder name.</p>


```csharp
public string FolderName { get; }
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Returns the CIM definition of the bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMBookmark GetDefinition()
```
### HasRangeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets a value indicating whether the bookmark contains a time extent.</p>


```csharp
public bool HasRangeExtent { get; }
```
### HasTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets a value indicating whether the bookmark contains a time extent.</p>


```csharp
public bool HasTimeExtent { get; }
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets the unique path of the map in which the bookmark belongs.</p>


```csharp
public string MapURI { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets the name of the bookmark.</p>


```csharp
public string Name { get; }
```
### Rename(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Changes the name of the bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Rename(string name)
```
### SetDefinition(CIMBookmark)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Updates the bookmark using a CIM definition of a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMBookmark bookmark)
```
### SetDescription(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Set the description for the Bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDescription(string description)
```
### SetThumbnail(BitmapSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Set the thumbnail for the Bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetThumbnail(BitmapSource thumbnail)
```
### Thumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Gets the thumbnail of the bookmark.</p>


```csharp
public ImageSource Thumbnail { get; }
```
### Update(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">Updates the bookmark to the current location and time of a map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Update(MapView mapView)
```
### VideoElapsedTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">The time elapsed in the video when the bookmark was created.</p>


```csharp
public double VideoElapsedTime { get; }
```
### VideoURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Bookmark.yml" sourcestartlinenumber="1">URI to the video.</p>


```csharp
public string VideoURI { get; }
```


