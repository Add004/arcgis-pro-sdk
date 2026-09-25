# EditingOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the application editing options.</p>


## Object Signature

```csharp
public class EditingOptions
```


## Members

### ActivateMoveAfterPaste

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets if Move tool is to be activated after all paste operations.</p>


```csharp
public bool ActivateMoveAfterPaste { get; set; }
```
### AllowMergeToCreateNonPlanarPolygons

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the merge tool merges z-aware polygons
when they overlap.</p>


```csharp
public bool AllowMergeToCreateNonPlanarPolygons { get; set; }
```
### AllowVertexEditingWhileSketching

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether vertex editing is allowed while sketching.</p>


```csharp
public bool AllowVertexEditingWhileSketching { get; set; }
```
### AnnotationFollowMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the feature linked annotation follow mode. This describes how new annotation aligns to the line or boundary feature it is following.</p>


```csharp
public AnnotationFollowMode AnnotationFollowMode { get; set; }
```
### AnnotationPlacementMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the feature linked annotation placement mode for new annotation relative to the direction of the line or boundary feature it is following.</p>


```csharp
public AnnotationPlacementMode AnnotationPlacementMode { get; set; }
```
### AutoApplyAttributeEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether attribute edits are automatically applied.</p>


```csharp
public bool AutoApplyAttributeEdits { get; set; }
```
### AutoSaveByTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether edits are to be saved by time or operation when <xref href="ArcGIS.Desktop.Core.EditingOptions.AutomaticallySaveEdits" data-throw-if-not-resolved="false"></xref> is true.</p>


```csharp
public bool AutoSaveByTime { get; set; }
```
### AutomaticallyFollowLinkedLineFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether feature linked annotation automatically follows linked line features.</p>


```csharp
public bool AutomaticallyFollowLinkedLineFeatures { get; set; }
```
### AutomaticallyFollowLinkedPolygonFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether feature linked annotation automatically follows linked polygon features.</p>


```csharp
public bool AutomaticallyFollowLinkedPolygonFeatures { get; set; }
```
### AutomaticallySaveEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether edits are to be automatically saved.</p>


```csharp
public bool AutomaticallySaveEdits { get; set; }
```
### CanSetSegmentSymbolOptions(SegmentSymbolOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Determines if the segment sketch symbol can be set.</p>


```csharp
public bool CanSetSegmentSymbolOptions(SegmentSymbolOptions segmentSymbol)
```
### CanSetVertexSymbolOptions(VertexSymbolType, VertexSymbolOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Determines if the vertex sketch symbol can be set.</p>


```csharp
public bool CanSetVertexSymbolOptions(VertexSymbolType symbolType, VertexSymbolOptions vertexSymbol)
```
### DeactivateToolOnSaveOrDiscard

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the active editing tool is deactivated when saving or discarding edits.</p>


```csharp
public bool DeactivateToolOnSaveOrDiscard { get; set; }
```
### DefaultFallbackTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets the default fallback tool.  This is the &quot;esri_mapping_exploreTool&quot;.</p>


```csharp
public string DefaultFallbackTool { get; }
```
### DragSketch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the sketch behavior on a touch pad (click + drag vs click-drag-click)</p>


```csharp
public bool DragSketch { get; set; }
```
### EnableAnnoResize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets option to enable resize for selected annotation feature.</p>


```csharp
public bool EnableAnnoResize { get; set; }
```
### EnableAnnoRotate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets option to enable rotation for selected annotation feature.</p>


```csharp
public bool EnableAnnoRotate { get; set; }
```
### EnableControlPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether to enable control points on the sketch</p>


```csharp
public bool EnableControlPoints { get; set; }
```
### EnableEditingFromEditTab

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether editing can be enabled and disabled from the Edit tab.</p>


```csharp
public bool EnableEditingFromEditTab { get; set; }
```
### EnableStereoEscape

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the Escape key is enabled as a shortcut to cancel the active tool in Stereo maps.</p>


```csharp
public bool EnableStereoEscape { get; set; }
```
### EnforceAttributeValidation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether attribute validation is enforced.</p>


```csharp
public bool EnforceAttributeValidation { get; set; }
```
### FallbackTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the current fallback tool.  This tool will be activated when an editing tool is deactivated.</p>


```csharp
public string FallbackTool { get; set; }
```
### FinishSketchOnDoubleClick

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether double-click is enabled as a shortcut for Finish when sketching.</p>


```csharp
public bool FinishSketchOnDoubleClick { get; set; }
```
### GetDefaultSegmentSymbolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets the default segment sketching symbol information.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SegmentSymbolOptions GetDefaultSegmentSymbolOptions()
```
### GetDefaultVertexSymbolOptions(VertexSymbolType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets the default symbol information for a vertex while sketching.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VertexSymbolOptions GetDefaultVertexSymbolOptions(VertexSymbolType symbolType)
```
### GetFallbackTools()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets the list of tools that are registered as possible fallback tools.</p>


```csharp
public IReadOnlyList<string> GetFallbackTools()
```
### GetSegmentSymbolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets the segment sketching symbol information.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SegmentSymbolOptions GetSegmentSymbolOptions()
```
### GetVertexSymbolOptions(VertexSymbolType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets the symbol for a vertex while sketching.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VertexSymbolOptions GetVertexSymbolOptions(VertexSymbolType symbolType)
```
### HighlightLayerOnSelectionChange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the layer should be highlighted in the attributes window selection view when the selection changes.</p>


```csharp
public bool HighlightLayerOnSelectionChange { get; set; }
```
### InitializeDefaultValuesOnSubtypeChange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether default values are initialized on a subtype change.</p>


```csharp
public bool InitializeDefaultValuesOnSubtypeChange { get; set; }
```
### IsDeflectionDefaultDirectionConstraint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether Deflection is the default direction constraint.  Set to false for Absolute to be the default direction constraint.</p>


```csharp
public bool IsDeflectionDefaultDirectionConstraint { get; set; }
```
### IsDirectionDefaultInputConstraint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether Direction is the default constraint for input mode.  Set to false for Distance to be the default constraint for input mode.</p>


```csharp
public bool IsDirectionDefaultInputConstraint { get; set; }
```
### IsSingleWorkspaceEditSession

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether only data from a single workspace can be edited within an edit session.
Specify the workspace to be edited using the</p>


```csharp
public bool IsSingleWorkspaceEditSession { get; set; }
```
### MagnifyToolbar

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the editing toolbar is magnified.</p>


```csharp
public bool MagnifyToolbar { get; set; }
```
### NewLayersEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether newly added layers are editable by default.</p>


```csharp
public bool NewLayersEditable { get; set; }
```
### SaveEditsInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the time interval (in minutes) after which edits will be saved if <xref href="ArcGIS.Desktop.Core.EditingOptions.AutomaticallySaveEdits" data-throw-if-not-resolved="false"></xref> is true and <xref href="ArcGIS.Desktop.Core.EditingOptions.AutoSaveByTime" data-throw-if-not-resolved="false"></xref> is true.</p>


```csharp
public int SaveEditsInterval { get; set; }
```
### SaveEditsOnProjectSave

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether edits are saved when saving project.</p>


```csharp
public bool SaveEditsOnProjectSave { get; set; }
```
### SaveEditsOperations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the number of operations after which edits will be saved if <xref href="ArcGIS.Desktop.Core.EditingOptions.AutomaticallySaveEdits" data-throw-if-not-resolved="false"></xref> is true and <xref href="ArcGIS.Desktop.Core.EditingOptions.AutoSaveByTime" data-throw-if-not-resolved="false"></xref> is false.</p>


```csharp
public int SaveEditsOperations { get; set; }
```
### SetSegmentSymbolOptions(SegmentSymbolOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Sets the segment sketch symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSegmentSymbolOptions(SegmentSymbolOptions segmentSymbol)
```
### SetVertexSymbolOptions(VertexSymbolType, VertexSymbolOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Sets the symbol for a vertex while sketching.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVertexSymbolOptions(VertexSymbolType symbolType, VertexSymbolOptions vertexSymbol)
```
### ShowDeleteDialog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the dialog to confirm deletes is displayed.</p>


```csharp
public bool ShowDeleteDialog { get; set; }
```
### ShowDiscardEditsDialog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the dialog to confirm discard edits is displayed.</p>


```csharp
public bool ShowDiscardEditsDialog { get; set; }
```
### ShowDynamicConstraints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether dynamic constraints are displayed in the map</p>


```csharp
public bool ShowDynamicConstraints { get; set; }
```
### ShowEditingToolbar

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the editing toolbar is visible.</p>


```csharp
public bool ShowEditingToolbar { get; set; }
```
### ShowFeatureSketchSymbology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether feature symbology is displayed in the sketch.</p>


```csharp
public bool ShowFeatureSketchSymbology { get; set; }
```
### ShowGeometricConstraints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether geometric constraints are displayed when drawing.</p>


```csharp
public bool ShowGeometricConstraints { get; set; }
```
### ShowSaveEditsDialog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether the dialog to confirm save edits is displayed.</p>


```csharp
public bool ShowSaveEditsDialog { get; set; }
```
### StretchGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether geometry is stretched proportionately when moving a vertex.</p>


```csharp
public bool StretchGeometry { get; set; }
```
### StretchTopology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether topology is stretched proportionately when moving a topology element.</p>


```csharp
public bool StretchTopology { get; set; }
```
### ToolbarPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the editing toolbar position.</p>


```csharp
public ToolbarPosition ToolbarPosition { get; set; }
```
### ToolbarSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the editing toolbar size.</p>


```csharp
public ToolbarSize ToolbarSize { get; set; }
```
### UncommitedAttributeEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the uncommitted attribute edits setting.</p>


```csharp
public UncommitedEditMode UncommitedAttributeEdits { get; set; }
```
### UncommitedGeometryEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets the uncommitted geometry edits setting.</p>


```csharp
public UncommitedEditMode UncommitedGeometryEdits { get; set; }
```
### UseAnnotationPlacementProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether feature linked annotation uses placement properties defined in the annotation class.</p>


```csharp
public bool UseAnnotationPlacementProperties { get; set; }
```
### WarnOnSubtypeChange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EditingOptions.yml" sourcestartlinenumber="1">Gets and sets whether a warning is displayed when subtypes are changed.</p>


```csharp
public bool WarnOnSubtypeChange { get; set; }
```


