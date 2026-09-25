# KnowledgeGraphLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">A knowledge graph layer is a composite layer with a knowledge graph as its
data source.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphLayer : CompositeLayerWithTables, IMetadataInfo, IMetadataSource, IStandaloneTableContainer, ILayerContainerEdit, ILayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">The knowledge graph layer contains knowledge graph feature layers and
knowledge graph tables. One knowledge graph feature layer is created within
the knowledge graph composite layer per entity and relationship type when the
entity and relationship instances can have spatial features. A standalone table
is created within the knowledge graph composite layer per entity and relationship
type that is nonspatial.<br></p>


## Members

### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Determines if a layer can be removed from the container.
Sublayers can be removed only if the knowledgegraph layer is on a map.</p>


```csharp
public bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Determines if the layers can be removed from the container.
Sublayers can be removed only if the knowledgegraph layer is on a map.</p>


```csharp
public bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### GetDatastore()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets the knowledge graph datastore associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraph GetDatastore()
```
### GetIDSet()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet" data-throw-if-not-resolved="false"></xref> for this Knowledge Graph layer.
That is the set of Named Object types and their corresponding set of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphLayerIDSet GetIDSet()
```
### GetKnowledgeGraphSubGraph()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph" data-throw-if-not-resolved="false"></xref> for the KnowledgeGraphLayer.  This is defined by the layer's <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet" data-throw-if-not-resolved="false"></xref>;
that is the set of Named Object types and their corresponding set of records that define this KnowledgeGraphLayer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMKnowledgeGraphSubGraph GetKnowledgeGraphSubGraph()
```
### GetPathOrServiceUri()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets the file path or service uri for the datastore associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetPathOrServiceUri()
```
### GetServiceUri()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Gets the service url for the datastore associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
[Obsolete("This method will be deleted at 4.0. Please use the GetPathOrServiceUri() method instead")]
public string GetServiceUri()
```
### MoveLayer(Layer, CompositeLayer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Move a layer to another position within the specified container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, CompositeLayer targetLayer, int position)
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Moves a layer to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, int position)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Removes a layer from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayer.yml" sourcestartlinenumber="1">Remove multiple layers from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayers(IEnumerable<Layer> layers)
```


