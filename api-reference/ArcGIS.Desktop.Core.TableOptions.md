# TableOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets the application table options.</p>


## Object Signature

```csharp
public class TableOptions
```


## Members

### ActivateMapViewAfterOperations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets if the mapview is to be activated after using Flash, Pan or Zoom from the table.</p>


```csharp
public bool ActivateMapViewAfterOperations { get; set; }
```
### AutoRefreshAfterChanges

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets if the table is refreshed when data changes are made by edits.</p>


```csharp
public bool AutoRefreshAfterChanges { get; set; }
```
### ColumnHeaderHeightType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets the column header height type</p>


```csharp
public TableRowHeightType ColumnHeaderHeightType { get; set; }
```
### DefaultFontName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Get the default font name.</p>


```csharp
public string DefaultFontName { get; }
```
### DefaultFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets the default font size.</p>


```csharp
public double DefaultFontSize { get; }
```
### DefaultHighlightColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets the default highlight color.</p>


```csharp
public CIMColor DefaultHighlightColor { get; }
```
### FilterByExtent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets if the table is filtered by the map extent when a new table is opened.</p>


```csharp
public bool FilterByExtent { get; set; }
```
### FilterByRange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets if the table is filtered by range when a new table is opened.</p>


```csharp
public bool FilterByRange { get; set; }
```
### FilterByTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets if the table if filtered by time when a new table is opened.</p>


```csharp
public bool FilterByTime { get; set; }
```
### FontName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets the font name.</p>


```csharp
public string FontName { get; set; }
```
### FontSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets the font size.</p>


```csharp
public double FontSize { get; set; }
```
### HideAddNewRow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets whether the &quot;Click to add new row&quot; option is hidden for feature class tables.</p>


```csharp
public bool HideAddNewRow { get; set; }
```
### HighlightColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets the highlight color.</p>


```csharp
public CIMColor HighlightColor { get; }
```
### HonorSelectionColorOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets whether selection color overrides are honored.</p>


```csharp
public bool HonorSelectionColorOverrides { get; set; }
```
### IsValidFontName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Determines if a specified font name is valid for use in the TableOptions.</p>


```csharp
public bool IsValidFontName(string fontName)
```
### IsValidFontSize(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Determines if a specified font size is valid for use in the TableOptions.</p>


```csharp
public bool IsValidFontSize(double fontSize)
```
### RowHeightType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Gets and sets the row height type.</p>


```csharp
public TableRowHeightType RowHeightType { get; set; }
```
### SetHighlightColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TableOptions.yml" sourcestartlinenumber="1">Sets the highlight color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetHighlightColor(CIMColor highlightColor)
```


