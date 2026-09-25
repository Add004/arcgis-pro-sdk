# LasDatasetLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Represents a LAS dataset layer.</p>


## Object Signature

```csharp
public sealed class LasDatasetLayer : SurfaceLayer, IMetadataInfo, IMetadataSource
```


## Members

### CanClassifyLasPoints(LasPointClassificationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Determines whether the specified classification edit can be performed on this LAS dataset layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanClassifyLasPoints(LasPointClassificationDescription editDescription)
```
### ClassifyLasPoints(LasPointClassificationDescription, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Applies the specified set of classification codes and / or classification flags to the
LAS points identified by the <xref href="ArcGIS.Desktop.Mapping.LasPointSelectionFilter" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ClassifyLasPoints(LasPointClassificationDescription editDescription, bool keepSelection)
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Clears the current selection for this layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelection()
```
### EyeDomeLightingRadius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the Eye Dome Lighting (EDL) radius value.  The EDL radius controls the width of effects.</p>


```csharp
public double EyeDomeLightingRadius { get; }
```
### EyeDomeLightingStrength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the Eye Dome Lighting (EDL) strength value. The EDL strength adjusts the intensity of the resulting effects.</p>


```csharp
public double EyeDomeLightingStrength { get; }
```
### GetActiveSurfaceConstraints()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the set of active surface constraints.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<SurfaceConstraint> GetActiveSurfaceConstraints()
```
### GetCustomSelectionProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the custom selection properties in use for this layer; that is the flag indicating if a custom selection color is used and the custom selection color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (bool useCustomSelectionColor, CIMColor customSelectionColor) GetCustomSelectionProperties()
```
### GetDisplayFilter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the current display filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasPointDisplayFilter GetDisplayFilter()
```
### GetElevationRangeFilter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the current elevation range filter.</p>


```csharp
public LasPointElevationRangeFilter GetElevationRangeFilter()
```
### GetElevationRangeFromDatasetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the minimum and maximum elevation values from the extent of the data contained in the layer's dataset.  The values are returned in meters.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (double minZ, double maxZ) GetElevationRangeFromDatasetExtent()
```
### GetLasDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the LAS dataset associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasDataset GetLasDataset()
```
### GetSelectVisiblePoints()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Determines if only visible points are selectable or not.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetSelectVisiblePoints()
```
### GetSelectableClassCodes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the class codes that are selectable.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<int> GetSelectableClassCodes()
```
### HasSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets whether the layer has a selection.</p>


```csharp
public bool HasSelection { get; }
```
### IsElevationRangeFilterEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets if the elevation range filter is enabled.</p>


```csharp
public bool IsElevationRangeFilterEnabled { get; }
```
### IsEyeDomeLightingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets whether Eye Dome Lighting (EDL) is enabled on the layer.</p>


```csharp
public bool IsEyeDomeLightingEnabled { get; }
```
### SearchPoints(LasPointFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Retrieves the points in the LAS dataset layer that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all points will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasPointCursor SearchPoints(LasPointFilter filter)
```
### SelectAsync(LasPointSelectionFilter, SelectionCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Selects LAS points based upon the specified filter.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<int> SelectAsync(LasPointSelectionFilter selectionFilter, SelectionCombinationMethod method = SelectionCombinationMethod.New)
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Gets the number of points selected in the layer.</p>


```csharp
public int SelectionCount { get; }
```
### SetActiveSurfaceConstraints(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the group of active surface constraints.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveSurfaceConstraints(List<string> surfaceConstraintNames)
```
### SetCustomSelectionColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the layer to display its selection in the specified color. Use null to specify that the layer should display its selection in
the default selection color defined in <xref href="ArcGIS.Desktop.Core.SelectionOptions.SelectionColor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCustomSelectionColor(CIMColor color)
```
### SetDisplayFilter(LasPointDisplayFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the display filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayFilter(LasPointDisplayFilter filter)
```
### SetDisplayFilter(LasPointDisplayFilterType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the classification codes, returns and flags for the display filter according to the specified filter type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayFilter(LasPointDisplayFilterType filtertype)
```
### SetDisplayFilter(List&lt;LasReturnType&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the returns for the display filter.  Other elements of the display filter are unchanged.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayFilter(List<LasReturnType> returns)
```
### SetDisplayFilter(List&lt;int&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the classification codes for the display filter.  Other elements of the display filter are unchanged.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayFilter(List<int> classCodes)
```
### SetElevationRangeFilter(LasPointElevationRangeFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the elevation range filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetElevationRangeFilter(LasPointElevationRangeFilter elevationFilter)
```
### SetElevationRangeFilter(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the elevation range filter with a specific minimum and maximum Z value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetElevationRangeFilter(double minZ, double maxZ)
```
### SetElevationRangeFilterEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the elevation range filter enabled state.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetElevationRangeFilterEnabled(bool enable)
```
### SetEyeDomeLightingEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Enables/disables eye dome lighting. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEyeDomeLightingEnabled(bool enabled)
```
### SetEyeDomeLightingRadius(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the Eye Dome Lighting (EDL) radius value. The EDL radius controls the width of effects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEyeDomeLightingRadius(double value)
```
### SetEyeDomeLightingStrength(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the Eye Dome Lighting (EDL) strength value. The EDL strength adjusts the intensity of the resulting effects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEyeDomeLightingStrength(double value)
```
### SetSelectVisiblePoints(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Specifies if only visible points are selectable or not.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectVisiblePoints(bool selectVisiblePoints)
```
### SetSelectableClassCodes(IEnumerable&lt;int&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the class codes that are selectable.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectableClassCodes(IEnumerable<int> classCodes)
```
### SetUseDefaultSelectionColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasDatasetLayer.yml" sourcestartlinenumber="1">Sets the layer to use the default selection color to display its selection.  The default selection color is defined in the Selection options.  See
<xref href="ArcGIS.Desktop.Core.SelectionOptions.SelectionColor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseDefaultSelectionColor()
```


