# GroupLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Represents a layer containing an editable collection of layers.</p>


## Object Signature

```csharp
public sealed class GroupLayer : CompositeLayerWithTables, IMetadataInfo, IMetadataSource, ILayerContainerEdit, ILayerContainer, IStandaloneTableContainerEdit, IStandaloneTableContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">To create a GroupLayer, you must call CreateGroupLayer() method of the <xref href="ArcGIS.Desktop.Mapping.LayerFactory?text=LayerFactory" data-throw-if-not-resolved="false"></xref> class, instead of directly using a constructor.</p>


## Members

### AddSymbolLayerDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Add Symbol Layer Drawing, SLD, to the group layer. After adding
SLD it will be enabled. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddSymbolLayerDrawing()
```
### CanAddSymbolLayerDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Determine whether the group layer can have Symbol Layer Drawing
added to its definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanAddSymbolLayerDrawing()
```
### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Determines if a layer can be removed from the container.</p>


```csharp
public bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Determines if the layers can be removed from the container.</p>


```csharp
public bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### CanSetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Gets if the mapMember supports time filtering and if the specified time parameters are valid.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public override bool CanSetTime(TimeParameters timeParams)
```
### GetUseSymbolLayerDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Gets whether the group layer is currently using Symbol Layer Drawing or not.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (bool useOnLayer, bool useOnParent) GetUseSymbolLayerDrawing()
```
### HasSymbolLayerDrawingAdded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Determine whether the group layer has Symbol Layer Drawing
added. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (bool addedOnLayer, bool addedOnParent) HasSymbolLayerDrawingAdded()
```
### MoveLayer(Layer, CompositeLayer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Move a layer to another position within the specified container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, CompositeLayer targetLayer, int position)
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Moves a layer to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, int position)
```
### MoveStandaloneTable(StandaloneTable, CompositeLayerWithTables, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Moves a StandaloneTable to a position within the specified targetLayer container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveStandaloneTable(StandaloneTable table, CompositeLayerWithTables targetLayer, int position)
```
### MoveStandaloneTable(StandaloneTable, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Moves a StandaloneTable to a position within this container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveStandaloneTable(StandaloneTable table, int position)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Removes a layer from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Remove multiple layers from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayers(IEnumerable<Layer> layers)
```
### RemoveStandaloneTable(StandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Removes the specified StandaloneTable from the container or from a child container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveStandaloneTable(StandaloneTable table)
```
### RemoveStandaloneTables(IEnumerable&lt;StandaloneTable&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Removes the specified StandaloneTables from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveStandaloneTables(IEnumerable<StandaloneTable> tables)
```
### SetSublayerVisibilityMode(SublayerVisibilityMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Sets the mode controlling the visibility of sublayers in the group layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSublayerVisibilityMode(SublayerVisibilityMode visibilityMode)
```
### SetUseSymbolLayerDrawing(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Sets whether Symbol Layer Drawing will be used on the group layer
or not. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseSymbolLayerDrawing(bool useSLD)
```
### SublayerVisibilityMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GroupLayer.yml" sourcestartlinenumber="1">Gets the mode controlling the visibility of sublayers.</p>


```csharp
public SublayerVisibilityMode SublayerVisibilityMode { get; }
```


