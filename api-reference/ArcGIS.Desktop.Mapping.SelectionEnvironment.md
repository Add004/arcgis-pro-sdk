# SelectionEnvironment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Defines the selection environment.</p>


## Object Signature

```csharp
public static class SelectionEnvironment
```


## Members

### CombinationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the selection combination mode.</p>


```csharp
public static SelectionCombinationMethod CombinationMethod { get; }
```
### DefaultColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the default selection color.</p>


```csharp
public static CIMColor DefaultColor { get; }
```
### DefaultHighlightColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the default highlight selection color.</p>


```csharp
public static CIMColor DefaultHighlightColor { get; }
```
### DefaultSelectionFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the default selection fill color.</p>


```csharp
public static CIMColor DefaultSelectionFillColor { get; }
```
### DefaultSelectionFillColorHatched

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets whether the default selection fill color (if any) will
be hatched.</p>


```csharp
public static bool DefaultSelectionFillColorHatched { get; }
```
### DefaultSelectionTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the default search toleraince in device units.</p>


```csharp
public static int DefaultSelectionTolerance { get; }
```
### EnableClickTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the value indicating whether click tolerance is enabled.</p>


```csharp
public static bool EnableClickTolerance { get; }
```
### KeepInvisibleFeatureSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets a value indicating whether to keep invisible features selected with a new selection.</p>


```csharp
public static bool KeepInvisibleFeatureSelected { get; }
```
### SaveSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets a value indicating whether to save layer and standalone table selection with maps.</p>


```csharp
public static bool SaveSelection { get; }
```
### SelectionMethod

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the selection method.</p>


```csharp
public static SelectionMethod SelectionMethod { get; }
```
### SelectionTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the search tolerance in device units.</p>


```csharp
public static int SelectionTolerance { get; }
```
### SetCombinationMethod(SelectionCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the selection combination mode. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetCombinationMethod(SelectionCombinationMethod combinationMethod)
```
### SetDefaultColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the default selection color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetDefaultColor(CIMColor color)
```
### SetDefaultHighlightColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the default highlight selection color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetDefaultHighlightColor(CIMColor color)
```
### SetDefaultHighlightColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the default highlight selection color.</p>


```csharp
public static Task SetDefaultHighlightColorAsync(CIMColor color)
```
### SetDefaultSelectionFillColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the default selection fill color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetDefaultSelectionFillColor(CIMColor color)
```
### SetDefaultSelectionFillColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the default selection fill color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task SetDefaultSelectionFillColorAsync(CIMColor color)
```
### SetDefaultSelectionFillColorHatched(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets whether the default selection fill color (if any) will be
hatched or solid. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetDefaultSelectionFillColorHatched(bool hatched)
```
### SetDefaultSelectionFillColorHatchedAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets whether the default selection fill color (if any) will be
hatched or solid.</p>


```csharp
public static Task SetDefaultSelectionFillColorHatchedAsync(bool hatched)
```
### SetEnableClickTolerance(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the value indicating whether click tolerance is enabled. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetEnableClickTolerance(bool enable)
```
### SetKeepInvisibleFeatureSelected(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets a value indicating whether to keep invisible features selected with a new selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetKeepInvisibleFeatureSelected(bool keepInvisibleFeatureSelected)
```
### SetSaveSelection(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets a value indicating whether to save layer and standalone table selection with maps. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetSaveSelection(bool saveSelection)
```
### SetSelectionMethod(SelectionMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the SelectionMethod. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetSelectionMethod(SelectionMethod selectionMethod)
```
### SetSelectionTolerance(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets the search tolerance in device units. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetSelectionTolerance(int tolerance)
```
### SetShowSelectionChip(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets a value indicating whether to display the Selection Chip, when coincident or overlapping features are selected. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetShowSelectionChip(bool showSelectionChip)
```
### SetShowSelectionGraphic(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Sets a value indicating whether to display the selection graphic during selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetShowSelectionGraphic(bool showSelectionGraphic)
```
### ShowSelectionChip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets a value indicating whether to display the Selection Chip, when coincident or overlapping features are selected.</p>


```csharp
public static bool ShowSelectionChip { get; }
```
### ShowSelectionGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets a value indicating whether to display the selection graphic during selection.</p>


```csharp
public static bool ShowSelectionGraphic { get; }
```
### SystemDefaultHighlightColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the system default highlight color.</p>


```csharp
public static CIMColor SystemDefaultHighlightColor { get; }
```
### SystemDefaultSelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the system default selection color.</p>


```csharp
public static CIMColor SystemDefaultSelectionColor { get; }
```
### SystemDefaultSelectionFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionEnvironment.yml" sourcestartlinenumber="1">Gets the system default selection fill color.</p>


```csharp
public static CIMColor SystemDefaultSelectionFillColor { get; }
```


