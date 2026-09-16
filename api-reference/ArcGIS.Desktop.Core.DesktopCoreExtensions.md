# DesktopCoreExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DesktopCoreExtensions.yml" sourcestartlinenumber="1">Extension methods for Desktop.Core classes</p>


## Object Signature

```csharp
public static class DesktopCoreExtensions
```


## Members

### CombinationMethod(SelectionOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DesktopCoreExtensions.yml" sourcestartlinenumber="1">Gets the selection combination mode.</p>


```csharp
public static SelectionCombinationMethod CombinationMethod(this SelectionOptions selectionOptions)
```
### SelectionMethod(SelectionOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DesktopCoreExtensions.yml" sourcestartlinenumber="1">Gets the selection method.</p>


```csharp
public static SelectionMethod SelectionMethod(this SelectionOptions selectionOptions)
```
### SetCombinationMethod(SelectionOptions, SelectionCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DesktopCoreExtensions.yml" sourcestartlinenumber="1">Sets the selection combination mode. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetCombinationMethod(this SelectionOptions selectionOptions, SelectionCombinationMethod combinationMethod)
```
### SetSelectionMethod(SelectionOptions, SelectionMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DesktopCoreExtensions.yml" sourcestartlinenumber="1">Sets the SelectionMethod. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetSelectionMethod(this SelectionOptions selectionOptions, SelectionMethod selectionMethod)
```


