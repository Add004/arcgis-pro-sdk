# SelectionOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets and sets the application selection options.</p>


## Object Signature

```csharp
public class SelectionOptions
```


## Members

### DefaultSelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the default selection color.</p>


```csharp
public CIMColor DefaultSelectionColor { get; }
```
### DefaultSelectionFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the default selection fill color.</p>


```csharp
public CIMColor DefaultSelectionFillColor { get; }
```
### DefaultSelectionTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the default search tolerance in device units.</p>


```csharp
public int DefaultSelectionTolerance { get; }
```
### EnableClickTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the value indicating whether click tolerance is enabled.</p>


```csharp
public bool EnableClickTolerance { get; }
```
### IsSelectionFillHatched

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets if the selection fill is hatched.</p>


```csharp
public bool IsSelectionFillHatched { get; }
```
### KeepInvisibleFeaturesSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets a value indicating whether to keep invisible features selected with a new selection.</p>


```csharp
public bool KeepInvisibleFeaturesSelected { get; }
```
### SaveSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets a value indicating whether to save layer and standalone table selection with maps.</p>


```csharp
public bool SaveSelection { get; }
```
### SelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the selection color.</p>


```csharp
public CIMColor SelectionColor { get; }
```
### SelectionFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the selection fill color.  A null value indicates that no color is applied to polygon interiors.</p>


```csharp
public CIMColor SelectionFillColor { get; }
```
### SelectionTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets the search tolerance in device units.</p>


```csharp
public int SelectionTolerance { get; }
```
### SetEnableClickTolerance(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets the value indicating whether click tolerance is enabled. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEnableClickTolerance(bool enable)
```
### SetKeepInvisibleFeaturesSelected(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets a value indicating whether to keep invisible features selected with a new selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetKeepInvisibleFeaturesSelected(bool keepInvisibleFeaturesSelected)
```
### SetSaveSelection(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets a value indicating whether to save layer and standalone table selection with maps. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSaveSelection(bool saveSelection)
```
### SetSelectionColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets the selection color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectionColor(CIMColor color)
```
### SetSelectionFillColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets the selection fill color.  Use this in conjunction with <xref href="ArcGIS.Desktop.Core.SelectionOptions.SetSelectionFillIsHatched(System.Boolean)" data-throw-if-not-resolved="false"></xref> to set
solid or hatched fills as appropriate.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectionFillColor(CIMColor color)
```
### SetSelectionFillIsHatched(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets the selection fill to be hatched or solid. Use this in conjunction with <xref href="ArcGIS.Desktop.Core.SelectionOptions.SetSelectionFillColor(ArcGIS.Core.CIM.CIMColor)" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectionFillIsHatched(bool isHhatched)
```
### SetSelectionTolerance(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets the search tolerance in device units. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectionTolerance(int tolerance)
```
### SetShowSelectionChip(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets a value indicating whether to display the Selection Chip, when coincident or overlapping features are selected. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowSelectionChip(bool showSelectionChip)
```
### SetShowSelectionGraphic(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Sets a value indicating whether to display the selection graphic during selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowSelectionGraphic(bool showSelectionGraphic)
```
### ShowSelectionChip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets a value indicating whether to display the Selection Chip, when coincident or overlapping features are selected.</p>


```csharp
public bool ShowSelectionChip { get; }
```
### ShowSelectionGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets a value indicating whether to display the selection graphic during selection.</p>


```csharp
public bool ShowSelectionGraphic { get; }
```
### UseSelectionFill

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SelectionOptions.yml" sourcestartlinenumber="1">Gets if a selection fill is applied to polygon interiors.</p>


```csharp
public bool UseSelectionFill { get; }
```


