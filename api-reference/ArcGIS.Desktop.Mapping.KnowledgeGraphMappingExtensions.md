# KnowledgeGraphMappingExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Contains extension methods to extend ArcGIS.Desktop.Mapping classes.</p>


## Object Signature

```csharp
public static class KnowledgeGraphMappingExtensions
```


## Members

### AppendToLinkChart(Map, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Appends a set of named object types and their records to the link chart map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void AppendToLinkChart(this Map linkChart, KnowledgeGraphLayerIDSet idSet)
```
### CanAppendToLinkChart(Map, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Determines if the set of named object types and their records can be appended to the link chart map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanAppendToLinkChart(this Map linkChart, KnowledgeGraphLayerIDSet idSet)
```
### CanClearLinkChartContent(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Determines if the content of the link chart map can be cleared.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanClearLinkChartContent(this Map linkChart)
```
### CanSetLinkChartContent(Map, KnowledgeGraphLayerIDSet, IDSetCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Determines if the set of named object types and their records can be applied to the link chart map using the
specified <xref href="ArcGIS.Desktop.Mapping.IDSetCombinationMethod" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanSetLinkChartContent(this Map linkChart, KnowledgeGraphLayerIDSet idSet, IDSetCombinationMethod combinationMethod)
```
### ClearLinkChartContent(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Clears the link chart map content.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ClearLinkChartContent(this Map linkChart)
```
### ClearRootNodes(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Clears the root nodes for the link chart map view.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ClearRootNodes(this MapView mapView)
```
### GetLinkChartLayout(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Gets the layout algorithm for the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeLinkChartLayoutAlgorithm GetLinkChartLayout(this MapView mapView)
```
### GetRootNodes(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Gets the set of root nodes as a MapMemberIDSet.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static MapMemberIDSet GetRootNodes(this MapView mapView)
```
### GetShowNonSpatialData(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Gets whether non spatial data are displayed for the knowledge graph layer in the link chart map view.</p>


```csharp
public static bool GetShowNonSpatialData(this MapView mapView)
```
### GetShowRootNodes(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Gets whether root nodes are displayed for the link chart map view.</p>


```csharp
public static bool GetShowRootNodes(this MapView mapView)
```
### SelectAllRootNodes(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Selects the existing set of root nodes defined on the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SelectionSet SelectAllRootNodes(this MapView mapView)
```
### SelectNonSpatialData(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Selects the existing set of non spatial data in the knowledge graph layer on the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SelectionSet SelectNonSpatialData(this MapView mapView)
```
### SelectRootNodes(MapView, MapMemberIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Sets AND selects the root nodes for the link chart map view.  Use an empty set of rootNodes to clear the existing set of root nodes and the selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SelectionSet SelectRootNodes(this MapView mapView, MapMemberIDSet rootNodes)
```
### SelectSpatialData(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Selects the existing set of spatial data in the knowledge graph layer on the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SelectionSet SelectSpatialData(this MapView mapView)
```
### SetLinkChartContent(Map, KnowledgeGraphLayerIDSet, IDSetCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Applies a set of named object types and their records to the link chart map using the specified <xref href="ArcGIS.Desktop.Mapping.IDSetCombinationMethod" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetLinkChartContent(this Map linkChart, KnowledgeGraphLayerIDSet idSet, IDSetCombinationMethod combinationMethod)
```
### SetLinkChartLayoutAsync(MapView, KnowledgeLinkChartLayoutAlgorithm)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Sets the layout algorithm for the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task SetLinkChartLayoutAsync(this MapView mapView, KnowledgeLinkChartLayoutAlgorithm algorithm)
```
### SetLinkChartLayoutAsync(MapView, KnowledgeLinkChartLayoutAlgorithm, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Sets the layout algorithm for the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task SetLinkChartLayoutAsync(this MapView mapView, KnowledgeLinkChartLayoutAlgorithm algorithm, bool forceLayoutUpdate)
```
### SetRootNodes(MapView, MapMemberIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Sets the root nodes for the link chart map view.  Use an empty set of rootNodes to clear the existing set of root nodes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetRootNodes(this MapView mapView, MapMemberIDSet rootNodes)
```
### SetShowNonSpatialData(MapView, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Sets whether non spatial data are displayed for the knowledge graph layer in the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetShowNonSpatialData(this MapView mapView, bool showNonSpatialData)
```
### SetShowRootNodes(MapView, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.yml" sourcestartlinenumber="1">Sets whether root nodes are displayed for the link chart map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetShowRootNodes(this MapView mapView, bool showRootNodes)
```


