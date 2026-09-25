# ItemFilters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Represents a filter that is used to narrow the list of items displayed in the Browse dialog box.</p>


## Object Signature

```csharp
public static class ItemFilters
```

## Remarks

<p>Filters are used in the Browse dialog box to provide a list of items that is appropriate for
    the task at hand. Filters allow appropriate items to be displayed and deny other items from being
    listed. Filters can also specify which places in the left panel are appropriate for a particular
    scenario. For example, in some cases it is appropriate to select items from the active portal, while
    in other cases it is only appropriate to select items from enterprise databases that have been added
    to your project.</p>
<p>In cases such as where the Browse dialog box is used to add data to a map, a large list of
    items is initially be presented, but additional filters are available in the filters drop-down list
    that let you narrow the list of items further. This is a composite filter.</p>


## Members

### Annotation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for annotation feature classes.</p>


```csharp
public static string Annotation { get; }
```
### Bim

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing BIM files and the feature classes they contain.</p>


```csharp
public static string Bim { get; }
```
### Cad

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing CAD datasets and the feature classes they contain.</p>


```csharp
public static string Cad { get; }
```
### Composite_AddToMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for items and datasets that can be added to a map. As a composite filter, the default filter allows you to browse for anything that is
supported, but focused filters are also available to browse just for layers or geodatabase items, for example, that you want to add to a map.</p>


```csharp
public static string Composite_AddToMap { get; }
```
### Composite_AddToStereoMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for items and datasets that can be added to a stereo map. As a composite filter, the default filter allows you to browse for anything that is
supported, but focused filters are also available to browse just for layers or geodatabase items, for example, that you want to add to a stereo map.</p>


```csharp
public static string Composite_AddToStereoMap { get; }
```
### Composite_ElevationSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for web layers and datasets that can be used to define the elevation surface of a globe. As a composite filter, the default
filter allows you to browse for anything that is supported, but focused filters are also available to browse just for images services, for example,
that you want to define the ground.</p>


```csharp
public static string Composite_ElevationSource { get; }
```
### Composite_Maps_Import

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for maps and layouts that can be imported to a project. As a composite filter, the default filter allows you to browse for anything that is
supported, but focused filters are also available to browse just for ArcGIS Pro map or layout files, for example, that you want to import.</p>


```csharp
public static string Composite_Maps_Import { get; }
```
### Databases

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of databases supported by ArcGIS Pro. Both database connections in a project and databases stored on a local or network computer
can be browsed.</p>


```csharp
public static string Databases { get; }
```
### Default_AddToMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all items or datasets that can be added to a map. This is the default filter in the composite_addToMap filter.</p>


```csharp
public static string Default_AddToMap { get; }
```
### Default_AddToStereoMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all items or datasets that can be added to a stereo map. This is the default filter in the composite_addToStereoMap filter.</p>


```csharp
public static string Default_AddToStereoMap { get; }
```
### Default_Import

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all items that can be imported to a project. This is the default filter in the composite_maps_import filter.</p>


```csharp
public static string Default_Import { get; }
```
### Dimensions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for dimension feature classes.</p>


```csharp
public static string Dimensions { get; }
```
### FeatureClasses_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of feature classes.</p>


```csharp
public static string FeatureClasses_All { get; }
```
### FeatureDatasets_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of feature datasets.</p>


```csharp
public static string FeatureDatasets_All { get; }
```
### Files_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for all file extensions.</p>


```csharp
public static string Files_All { get; }
```
### Folders

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing folder connections in the project and folders on a local or network computer.</p>


```csharp
public static string Folders { get; }
```
### GeodatabaseItems_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of items stored in a geodatabase.</p>


```csharp
public static string GeodatabaseItems_All { get; }
```
### Geodatabases

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of geodatabases supported by ArcGIS Pro. Both database connections in a project and databases stored on a local or network computer
can be browsed.</p>


```csharp
public static string Geodatabases { get; }
```
### Kml

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing Keyhole Markup Language files.</p>


```csharp
public static string Kml { get; }
```
### Layers_AllFileTypes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing layer files and layer packages available from the active portal and from a local or network computer.</p>


```csharp
public static string Layers_AllFileTypes { get; }
```
### Locators_AllTypes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of locators, including locator files and ArcGIS Server geocoding services.</p>


```csharp
public static string Locators_AllTypes { get; }
```
### Maps_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing maps in the project and all types of maps stored on a local or network computer.</p>


```csharp
public static string Maps_All { get; }
```
### Packages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of packages available from the active portal and stored on a local or network computer.</p>


```csharp
public static string Packages { get; }
```
### Project_Templates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing project templates available from the active portal and from a local or network computer.</p>


```csharp
public static string Project_Templates { get; }
```
### Projects

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing projects and project packages available from the active portal and from a local or network computer.</p>


```csharp
public static string Projects { get; }
```
### Rasters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of rasters, including mosaic datasets and file-based raster datasets.</p>


```csharp
public static string Rasters { get; }
```
### Services_AddToMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of web layers from the active portal and services from server connections in the project that can be added to maps.</p>


```csharp
public static string Services_AddToMap { get; }
```
### Services_AddToStereoMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of web layers from the active portal and services from server connections in the project that can be added to stereo maps.</p>


```csharp
public static string Services_AddToStereoMap { get; }
```
### Services_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of web layers from the active portal and services from server connections in the project that can be used in ArcGIS Pro.</p>


```csharp
public static string Services_All { get; }
```
### Services_Feature

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing feature services from the active portal and services from server connections in the project that can be added to maps.</p>


```csharp
public static string Services_Feature { get; }
```
### Services_Image

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing image services from the active portal and services from server connections in the project that can be added to maps.</p>


```csharp
public static string Services_Image { get; }
```
### Services_Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing map services from the active portal and services from server connections in the project that can be added to maps.</p>


```csharp
public static string Services_Map { get; }
```
### Shapefiles

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for shapefiles stored on a local or network computer.</p>


```csharp
public static string Shapefiles { get; }
```
### StyleFiles

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing styles accessed from the active portal or stored on a local or network computer.</p>


```csharp
public static string StyleFiles { get; }
```
### Tables_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of tables.</p>


```csharp
public static string Tables_All { get; }
```
### TaskFiles

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for task files stored on a local or network computer.</p>


```csharp
public static string TaskFiles { get; }
```
### TextFiles

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing all types of text files.</p>


```csharp
public static string TextFiles { get; }
```
### TinDatasets

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for TIN datasets stored on a local or network computer.</p>


```csharp
public static string TinDatasets { get; }
```
### Toolboxes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for all types of toolboxes.</p>


```csharp
public static string Toolboxes { get; }
```
### Tools

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for tools stored in toolboxes.</p>


```csharp
public static string Tools { get; }
```
### Videos

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Support browsing for video files.</p>


```csharp
public static string Videos { get; }
```
### Workspaces_All

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ItemFilters.yml" sourcestartlinenumber="1">Supports browsing for all types of workspaces, including folders, geodatabases, and feature datasets.</p>


```csharp
public static string Workspaces_All { get; }
```


