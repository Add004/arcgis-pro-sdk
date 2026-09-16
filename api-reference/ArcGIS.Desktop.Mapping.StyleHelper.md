# StyleHelper

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Provides methods for managing styles in ArcGIS Pro projects.</p>


## Object Signature

```csharp
public static class StyleHelper
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">The methods in this class can be used for creating new style files,  adding or removing styles from a project,
searching for and retrieving items from a style and for adding or removing items from a particular style.</p>


## Members

### AddItem(StyleProjectItem, StyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Adds a style item to a style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void AddItem(this StyleProjectItem styleProjectItem, StyleItem item)
```
### AddStyle(Project, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Adds the specified style to the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void AddStyle(this Project project, string styleName)
```
### CreateMobileStyle(Project, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Creates a new mobile style file (.stylx) on disk and adds the mobile style to the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void CreateMobileStyle(this Project project, string styleName)
```
### CreateStyle(Project, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Creates a new style file (.stylx) on disk and adds the style to the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void CreateStyle(this Project project, string styleName)
```
### LookupItem(StyleProjectItem, StyleItemType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Retrieves a specific style item from a style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static StyleItem LookupItem(this StyleProjectItem styleProjectItem, StyleItemType type, string key)
```
### RemoveItem(StyleProjectItem, StyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Removes a style item from a style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void RemoveItem(this StyleProjectItem styleProjectItem, StyleItem item)
```
### RemoveStyle(Project, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Removes the specified style from the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void RemoveStyle(this Project project, string styleName)
```
### SearchColorRamps(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of color ramp style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<ColorRampStyleItem> SearchColorRamps(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchColors(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of color style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<ColorStyleItem> SearchColors(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchDimensionStyles(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of dimension style style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<DimensionStyleStyleItem> SearchDimensionStyles(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchGrids(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of grid style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<GridStyleItem> SearchGrids(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchLabelPlacements(StyleProjectItem, StyleItemType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of label placement style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<LabelPlacementStyleItem> SearchLabelPlacements(this StyleProjectItem styleProjectItem, StyleItemType type, string searchString)
```
### SearchLegendItems(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of legend item style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<LegendItemStyleItem> SearchLegendItems(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchLegendPatches(StyleProjectItem, StyleItemType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of line or area legend patch style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<LegendPatchStyleItem> SearchLegendPatches(this StyleProjectItem styleProjectItem, StyleItemType itemType, string searchString)
```
### SearchLegends(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of legend style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<LegendStyleItem> SearchLegends(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchMapSurrounds(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of map surround style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<MapSurroundStyleItem> SearchMapSurrounds(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchNorthArrows(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of north arrow style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<NorthArrowStyleItem> SearchNorthArrows(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchScaleBars(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of scale bar style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<ScaleBarStyleItem> SearchScaleBars(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchSymbols(StyleProjectItem, StyleItemType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of symbol style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<SymbolStyleItem> SearchSymbols(this StyleProjectItem styleProjectItem, StyleItemType type, string searchString)
```
### SearchTableFrameFields(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of table frame field style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<TableFrameFieldStyleItem> SearchTableFrameFields(this StyleProjectItem styleProjectItem, string searchString)
```
### SearchTableFrames(StyleProjectItem, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Returns a collection of table frame style items that satisfy the search criteria. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<TableFrameStyleItem> SearchTableFrames(this StyleProjectItem styleProjectItem, string searchString)
```
### UpdateItem(StyleProjectItem, StyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Updates a style item from a style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UpdateItem(this StyleProjectItem styleProjectItem, StyleItem item)
```
### UpgradeStyle(StyleProjectItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StyleHelper.yml" sourcestartlinenumber="1">Upgrades the specified style to the current ArcGIS Pro version. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool UpgradeStyle(this StyleProjectItem styleProjectItem)
```


