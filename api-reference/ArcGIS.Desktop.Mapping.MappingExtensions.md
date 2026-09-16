# MappingExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Extension methods for Mapping objects.</p>


## Object Signature

```csharp
public static class MappingExtensions
```


## Members

### AddComponentTemplate(CIMGroupEditingTemplate, Layer, string, GroupTemplateBuilderMethods, IDictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Adds a component part to the group template.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static CIMGroupEditingTemplate AddComponentTemplate(this CIMGroupEditingTemplate groupTemplate, Layer layer, string templateName, GroupTemplateBuilderMethods builderMethod, IDictionary<string, object> options = null)
```
### AddDiagramLayer(Map, NetworkDiagram)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add a diagram layer to a diagram map.</p>


```csharp
public static DiagramLayer AddDiagramLayer(this Map map, NetworkDiagram networkDiagram)
```
### AddDiagramLayerAsync(Map, NetworkDiagram)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add a diagram layer to a diagram map.</p>


```csharp
public static Task<DiagramLayer> AddDiagramLayerAsync(this Map map, NetworkDiagram networkDiagram)
```
### AddOverlay(MapView, CIMGraphic, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, CIMGraphic graphic, double referenceScale = -1)
```
### AddOverlay(MapView, CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, CIMGraphic graphic, double referenceScale, double showThrough)
```
### AddOverlay(MapView, Geometry, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, Geometry geometry, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlay(MapView, Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### AddOverlay(MapView, Layer, long, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic for a feature on the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, Layer layer, long oid, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlay(MapView, IEnumerable&lt;CIMGraphic&gt;, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, IEnumerable<CIMGraphic> graphics, double referenceScale = -1)
```
### AddOverlay(MapView, IEnumerable&lt;CIMGraphic&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
public static IDisposable AddOverlay(this MapView mapView, IEnumerable<CIMGraphic> graphics, double referenceScale, double showThrough)
```
### AddOverlayAsync(MapView, CIMGraphic, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, CIMGraphic graphic, double referenceScale = -1)
```
### AddOverlayAsync(MapView, CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, CIMGraphic graphic, double referenceScale, double showThrough)
```
### AddOverlayAsync(MapView, Geometry, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, Geometry geometry, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlayAsync(MapView, Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### AddOverlayAsync(MapView, Layer, long, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add an overlay graphic for a feature on the map view. This is only supported in 2D.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, Layer layer, long oid, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlayAsync(MapView, IEnumerable&lt;CIMGraphic&gt;, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, IEnumerable<CIMGraphic> graphics, double referenceScale = -1)
```
### AddOverlayAsync(MapView, IEnumerable&lt;CIMGraphic&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
public static Task<IDisposable> AddOverlayAsync(this MapView mapView, IEnumerable<CIMGraphic> graphics, double referenceScale, double showThrough)
```
### AreTemplatesLoaded(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets whether templates have been loaded for the specified map member.</p>


```csharp
public static bool AreTemplatesLoaded(this MapMember mapMember)
```
### AutoGenerateTemplates(MapMember, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Generate feature templates for a layer or standalone-table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool AutoGenerateTemplates(this MapMember mapMember, bool forceCreate = false)
```
### BuildMapTopologyGraph&lt;T&gt;(Map, Action&lt;TopologyGraph&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Build the Map Topology Graph.</p>


```csharp
public static void BuildMapTopologyGraph<T>(this Map map, Action<TopologyGraph> action)
```
### BuildMapTopologyGraph&lt;T&gt;(MapView, Action&lt;TopologyGraph&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Build the Map Topology Graph.</p>


```csharp
public static void BuildMapTopologyGraph<T>(this MapView mapView, Action<TopologyGraph> action)
```
### CanClearTopology(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets if the active topology can be cleared. That is; the active topology cam be set to &quot;No Topology&quot;.</p>


```csharp
public static bool CanClearTopology(this Map map)
```
### CanEditData(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Checks if the data represented by the map member can be edited.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanEditData(this MapMember mapMember)
```
### CanSetActiveTopology(Map, TopologyProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets if the active topology can be set.  Topologies are only supported for 2D non-stereo maps.</p>


```csharp
public static bool CanSetActiveTopology(this Map map, TopologyProperties topologyProperties)
```
### CanSetActiveTopology(Map, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets if the active topology can be set.  Topologies are only supported for 2D non-stereo maps.</p>


```csharp
public static bool CanSetActiveTopology(this Map map, string topologyName)
```
### CanSetMapTopology(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets if the active topology can be set to a MapTopology.  Map topologies are only supported for 2D non-stereo maps.</p>


```csharp
public static bool CanSetMapTopology(this Map map)
```
### ClearSketchAsync(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Clears the current sketch in the view.</p>


```csharp
public static Task ClearSketchAsync(this MapView mapView)
```
### ClearTopologyAsync(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Clears the active topology.  That is; sets the active topology to &quot;No Topology&quot;.</p>


```csharp
public static Task<TopologyProperties> ClearTopologyAsync(this Map map)
```
### CreateGroupTemplateDefinition(BasicFeatureLayer, string, string, string, IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Creates a new group template object using the specified definition. Adds the base template specified to the group template as the base part.
This method must be called on the MCT. Use QueuedTask.Run.
Use this method in conjunction with calls to
<xref href="ArcGIS.Desktop.Mapping.MappingExtensions.AddComponentTemplate(ArcGIS.Core.CIM.CIMGroupEditingTemplate%2cArcGIS.Desktop.Mapping.Layer%2cSystem.String%2cArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods%2cSystem.Collections.Generic.IDictionary%7bSystem.String%2cSystem.Object%7d)" data-throw-if-not-resolved="false"></xref>
for each component part. Once the group template is fully defined, use
<xref href="ArcGIS.Desktop.Mapping.MappingExtensions.CreateTemplate(ArcGIS.Desktop.Mapping.MapMember%2cArcGIS.Core.CIM.CIMEditingTemplate)" data-throw-if-not-resolved="false"></xref> to add the template to the template manager.</p>


```csharp
public static CIMGroupEditingTemplate CreateGroupTemplateDefinition(this BasicFeatureLayer layer, string groupTemplateName, string baseTemplateName, string description = "", IEnumerable<string> tags = null)
```
### CreatePresetTemplate(Layer, string, SelectionSet, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Creates a new preset template from the specified set of features.</p>


```csharp
public static EditingTemplate CreatePresetTemplate(this Layer layer, string templateName, SelectionSet features, MapPoint hotPoint = null)
```
### CreateTemplate(MapMember, CIMEditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Creates a new template using the specified definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static EditingTemplate CreateTemplate(this MapMember mapMember, CIMEditingTemplate templateDef)
```
### CreateTemplate(MapMember, string, string, Inspector, string, string[], string[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Creates a new template using the specified definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static EditingTemplate CreateTemplate(this MapMember mapMember, string templateName, string description = "", Inspector inspector = null, string defaultTool = "", string[] tags = null, string[] toolFilter = null)
```
### FlattenLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets an enumeration of layers. Removes group layers and recurses their sublayers
to add them to the list.</p>


```csharp
public static IEnumerable<Layer> FlattenLayers(IEnumerable<Layer> layers)
```
### GetActiveTopologyAsync(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets the active topology properties from the map.</p>


```csharp
public static Task<TopologyProperties> GetActiveTopologyAsync(this Map map)
```
### GetAvailableTopologiesAsync(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets the list of available topologies for the map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task<IReadOnlyList<TopologyProperties>> GetAvailableTopologiesAsync(this Map map)
```
### GetCurrentSketchAsync(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets the current geometry of the sketch without finishing it.</p>


```csharp
public static Task<Geometry> GetCurrentSketchAsync(this MapView mapView)
```
### GetSketchType(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets the type of geometry for the current sketch.</p>


```csharp
public static SketchGeometryType? GetSketchType(this MapView mapView)
```
### GetTemplate(MapMember, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets a template by name for a map member. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static EditingTemplate GetTemplate(this MapMember mapMember, string name)
```
### GetTemplates(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets all templates for a map member. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<EditingTemplate> GetTemplates(this MapMember mapMember)
```
### GetTemplatesAsFlattenedList(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets all templates for a map member, including templates for any children. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<EditingTemplate> GetTemplatesAsFlattenedList(this MapMember mapMember)
```
### GetTopologyAsync(Map, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets the set of topology properties for the specified topology name.</p>


```csharp
public static Task<TopologyProperties> GetTopologyAsync(this Map map, string topologyName)
```
### Inspect(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Loads a row into a new inspector instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Inspector Inspect(this MapMember mapMember, long oid)
```
### IsControlledByParcelFabricAsync(Layer, ParcelFabricType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Gets whether the layer is controlled by a parcel fabric of the specified type.</p>


```csharp
public static Task<bool> IsControlledByParcelFabricAsync(this Layer layer, ParcelFabricType parcelFabricType)
```
### RemoveTemplate(MapMember, EditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Removes the specified template.</p>


```csharp
public static void RemoveTemplate(this MapMember mapMember, EditingTemplate template)
```
### RemoveTemplate(MapMember, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Removes a template from a map member.</p>


```csharp
public static void RemoveTemplate(this MapMember mapMember, string name)
```
### SelectElements(MapView, Geometry, SelectionCombinationMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Select elements on all visible graphics layers that visually intersect a geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Element> SelectElements(this MapView mapView, Geometry geometry, SelectionCombinationMethod method = 0, bool isWhollyWithin = false)
```
### SelectElements(MapView, GraphicsLayer, Geometry, SelectionCombinationMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Select elements on a graphics layer that visually intersect a geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Element> SelectElements(this MapView mapView, GraphicsLayer graphicsLayer, Geometry geometry, SelectionCombinationMethod method = 0, bool isWhollyWithin = false)
```
### SetActiveTopologyAsync(Map, TopologyProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Sets the active topology for the map to the set of specified topology properties.</p>


```csharp
public static Task<TopologyProperties> SetActiveTopologyAsync(this Map map, TopologyProperties topologyProperties)
```
### SetActiveTopologyAsync(Map, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Sets the active topology for the map to the specified topology name.</p>


```csharp
public static Task<TopologyProperties> SetActiveTopologyAsync(this Map map, string topologyName)
```
### SetCurrentSketchAsync(MapView, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Sets the current geometry of the sketch without finishing it.</p>


```csharp
public static Task SetCurrentSketchAsync(this MapView mapView, Geometry geometry)
```
### SetMapTopologyAsync(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Sets the active topology to the map topology.</p>


```csharp
public static Task<TopologyProperties> SetMapTopologyAsync(this Map map)
```
### TransformToGlobalID(BasicFeatureLayer, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Translate the objectIDs to globalIDs.</p>


```csharp
public static List<Guid> TransformToGlobalID(this BasicFeatureLayer layer, IEnumerable<long> objectIDs)
```
### TransformToGlobalID(StandaloneTable, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Translate the objectIDs to globalIDs.</p>


```csharp
public static List<Guid> TransformToGlobalID(this StandaloneTable table, IEnumerable<long> objectIDs)
```
### TransformToObjectIDs(BasicFeatureLayer, IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Translate the globalIDs to objectIDs.</p>


```csharp
public static List<long> TransformToObjectIDs(this BasicFeatureLayer layer, IEnumerable<Guid> globalIDs)
```
### TransformToObjectIDs(StandaloneTable, IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Translate the globalIDs to objectIDs.</p>


```csharp
public static List<long> TransformToObjectIDs(this StandaloneTable table, IEnumerable<Guid> globalIDs)
```
### UpdateOverlay(MapView, IEnumerable&lt;IDisposable&gt;, IEnumerable&lt;Geometry&gt;, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the geometry and symbol for a set of overlay graphics on the map view. Each overlay is drawn with the same symbol.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IEnumerable<IDisposable> disposables, IEnumerable<Geometry> geometries, CIMSymbolReference symbol, double referenceScale)
```
### UpdateOverlay(MapView, IEnumerable&lt;IDisposable&gt;, IEnumerable&lt;Geometry&gt;, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the geometry and symbol for a set of overlay graphics on the map view. Each overlay is drawn with the same symbol.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IEnumerable<IDisposable> disposables, IEnumerable<Geometry> geometries, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### UpdateOverlay(MapView, IDisposable, CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the graphic for an overlay graphic on the map view.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IDisposable disposable, CIMGraphic graphic, double referenceScale, double showThrough)
```
### UpdateOverlay(MapView, IDisposable, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the geometry for an overlay graphic on the map view.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IDisposable disposable, Geometry geometry)
```
### UpdateOverlay(MapView, IDisposable, Geometry, CIMSymbolReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map view.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IDisposable disposable, Geometry geometry, CIMSymbolReference symbol)
```
### UpdateOverlay(MapView, IDisposable, Geometry, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map view.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IDisposable disposable, Geometry geometry, CIMSymbolReference symbol, double referenceScale)
```
### UpdateOverlay(MapView, IDisposable, Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map view.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IDisposable disposable, Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### UpdateOverlay(MapView, IDisposable, IEnumerable&lt;CIMGraphic&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MappingExtensions.yml" sourcestartlinenumber="1">Updates the graphics for an overlay graphic on the map view.</p>


```csharp
public static bool UpdateOverlay(this MapView mapView, IDisposable disposable, IEnumerable<CIMGraphic> graphics, double referenceScale, double showThrough)
```


