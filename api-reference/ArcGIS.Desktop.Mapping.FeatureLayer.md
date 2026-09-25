# FeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Represents a layer with a collection of features and their visual representation and editing (when permitted).</p>


## Object Signature

```csharp
public class FeatureLayer : BasicFeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">To create a FeatureLayer, you must call CreateFeatureLayer or CreateLayer method of the <xref href="ArcGIS.Desktop.Mapping.LayerFactory?text=LayerFactory" data-throw-if-not-resolved="false"></xref> class, instead of directly using a constructor.</p>


## Members

### AddLabelClass(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Adds a label class to the layer's label class collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddLabelClass(string labelClassName)
```
### AddSymbolLayerDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Add Symbol Layer Drawing, SLD, to the feature layer. After adding
SLD it will be enabled.This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddSymbolLayerDrawing()
```
### ArePreviousObservationsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether Previous Observations will be displayed.</p>


```csharp
public bool ArePreviousObservationsVisible { get; }
```
### AreTrackLinesVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether Track Line segments will be displayed.</p>


```csharp
public bool AreTrackLinesVisible { get; }
```
### CanAddSymbolLayerDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Determine whether the feature layer can have Symbol Layer Drawing
added to its definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanAddSymbolLayerDrawing()
```
### CanCreateRenderer(RendererDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Determines whether a renderer can be created and is valid for the feature layer using the specified <xref href="ArcGIS.Desktop.Mapping.RendererDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanCreateRenderer(RendererDefinition rendererDefinition)
```
### CanLookupSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Determines whether the layer's renderer type supports symbol lookup.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanLookupSymbol()
```
### CanSetRenderer(CIMRenderer, FeatureRendererTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Determines whether a renderer is valid for the feature layer and can be updated.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSetRenderer(CIMRenderer renderer, FeatureRendererTarget featureRendererTarget = FeatureRendererTarget.Default)
```
### ClearFeatureDrawOrder()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Clear the existing feature drawing order. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public void ClearFeatureDrawOrder()
```
### CreateRenderer(RendererDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Creates a renderer to a feature layer using a RendererDefinition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderer CreateRenderer(RendererDefinition rendererDefinition)
```
### GetCanSetFeatureDrawOrder(List&lt;CIMFeatureSortInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether or not the given feature draw order can be set on
the layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanSetFeatureDrawOrder(List<CIMFeatureSortInfo> drawingOrder)
```
### GetCanSetFeatureDrawOrder(string, SortOrderType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether or not the given feature draw order can be set on
the layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanSetFeatureDrawOrder(string fieldName, SortOrderType sortDirection)
```
### GetFeatureClass()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Returns the underlying <xref href="ArcGIS.Core.Data.FeatureClass?text=FeatureClass" data-throw-if-not-resolved="false"></xref> that the feature layer is pointing to.
A FeatureClass is a collection of spatial entities, modeled as objects with properties and behavior.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetFeatureClass()
```
### GetFeatureDrawOrder()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets the current feature drawing order info.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<CIMFeatureSortInfo> GetFeatureDrawOrder()
```
### GetIsFeatureDrawOrderSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether or not feature drawing order is supported on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual bool GetIsFeatureDrawOrderSupported()
```
### GetRenderer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Returns the renderer used to draw the feature layer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderer GetRenderer()
```
### GetRenderer(FeatureRendererTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Returns the renderer used to draw the feature layer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderer GetRenderer(FeatureRendererTarget featureRendererTarget)
```
### GetUseSymbolLayerDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether the layer or a parent group layer is currently using Symbol
Layer Drawing or not. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (bool useOnLayer, bool useOnParent) GetUseSymbolLayerDrawing()
```
### HasSymbolLayerDrawingAdded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Determine whether the feature layer or a parent group layer has Symbol
Layer Drawing added. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (bool addedOnLayer, bool addedOnParent) HasSymbolLayerDrawingAdded()
```
### IsLabelVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether labels are drawing.</p>


```csharp
public bool IsLabelVisible { get; }
```
### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether feature snapping is enabled.</p>


```csharp
public bool IsSnappable { get; }
```
### IsSubtypeLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether the feature layer is a member of <xref href="ArcGIS.Desktop.Mapping.SubtypeGroupLayer" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsSubtypeLayer { get; }
```
### IsTrackAware

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether this Feature Layer supports track related functionality.</p>


```csharp
public bool IsTrackAware { get; }
```
### LabelClasses

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets the available label classes for the feature layer.</p>


```csharp
public ReadOnlyObservableCollection<LabelClass> LabelClasses { get; }
```
### LookupSymbol(long, MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Looks up the symbol for the corresponding feature identified by the object id.
This method will return null when the input OID is not part of the feature layer definition or if the renderer returns a null symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMSymbol LookupSymbol(long oid, MapView view)
```
### PreviousObservationsCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets the maximum number of Previous Observations to be displayed for each track.</p>


```csharp
public int PreviousObservationsCount { get; }
```
### RecalculateRenderer(FeatureRendererTarget, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Updates the renderer based on updated values from the data source.
For example, if a new unique value gets added to the FeatureClass, in case of unique value renderer, it gets updated with the newly added value.
Similarly with class breaks renderer, it tries best to preserve the number of class breaks and recalculates the break values based on the updated values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RecalculateRenderer(FeatureRendererTarget featureRendererTarget, bool generateAllUniqueValues, bool preserveSymbols = true)
```
### RecalculateRenderer(bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Updates the renderer based on updated values from the data source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RecalculateRenderer(bool generateAllUniqueValues, bool preserveSymbols = true)
```
### RemoveLabelClass(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Removes a label class from the layer's label class collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLabelClass(string labelClassName)
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether symbols are scaled based on the reference scale.</p>


```csharp
public bool ScaleSymbols { get; }
```
### SetFeatureDrawOrder(List&lt;CIMFeatureSortInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Set the layer feature drawing order. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public void SetFeatureDrawOrder(List<CIMFeatureSortInfo> drawingOrder)
```
### SetFeatureDrawOrder(string, SortOrderType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Set the layer feature drawing order. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public void SetFeatureDrawOrder(string fieldName, SortOrderType sortDirection)
```
### SetLabelVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Toggles the feature layer's label's visibility.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLabelVisibility(bool isLabelVisible)
```
### SetPreviousObservationsCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Specifies the maximum number of previous observations to be displayed for each track.</p>


```csharp
public void SetPreviousObservationsCount(int previousObservationsCount)
```
### SetPreviousObservationsVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Specifies whether to display previous observations or not.</p>


```csharp
public void SetPreviousObservationsVisibility(bool previousObservationsVisible)
```
### SetRenderer(CIMRenderer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Specifies the feature layer's renderer object which determines how the layer draws.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMRenderer renderer)
```
### SetRenderer(CIMRenderer, FeatureRendererTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Specifies the feature layer's renderer object which determines how the layer draws.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMRenderer renderer, FeatureRendererTarget featureRendererTarget)
```
### SetScaleSymbols(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Toggles whether all symbol and text sizes varies as the map scale changes based on the RefereceScale set on the map the layer belongs to.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetScaleSymbols(bool scaleSymbols)
```
### SetSnappable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Enables or disables snapping on the feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSnappable(bool isSnappable)
```
### SetTrackLinesVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Specifies whether to display Track Lines or not.</p>


```csharp
public void SetTrackLinesVisibility(bool trackLinesVisible)
```
### SetUseSymbolLayerDrawing(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Sets whether Symbol Layer Drawing will be used on the feature layer
or not. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseSymbolLayerDrawing(bool useSLD)
```
### SetUsesRealWorldSymbolSizes(bool, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Specifies to use real world symbol size in 3D based on the mapScale.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUsesRealWorldSymbolSizes(bool usesRealWorldSymbolSizes, double mapScale = -1)
```
### SubtypeValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets the subtype value that is used in the feature layer definition.</p>


```csharp
public int SubtypeValue { get; }
```
### TrackIdFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets the name of the TrackId field.</p>


```csharp
public string TrackIdFieldName { get; }
```
### TrackType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets the nature of the tracking data present in this feature layer.</p>


```csharp
public TrackType TrackType { get; }
```
### UsesRealWorldSymbolSizes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayer.yml" sourcestartlinenumber="1">Gets whether real world symbol size is used.</p>


```csharp
public bool UsesRealWorldSymbolSizes { get; }
```


