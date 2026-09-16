# NetworkDiagram

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Represents a network diagram.</p>


## Object Signature

```csharp
public sealed class NetworkDiagram : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">New network diagrams can be created using the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.CreateNetworkDiagram(ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate%2cSystem.Collections.Generic.IEnumerable%7bSystem.Guid%7d)" data-throw-if-not-resolved="false"></xref> factory method.
Existing network diagrams can be retrieved from the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramManager" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref> classes.</p>


## Members

### AddFlag(NetworkDiagramFlagType, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Adds a flag in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddFlag(NetworkDiagramFlagType flagType, int diagramElementID)
```
### Append(IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Appends features to this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Append(IEnumerable<Guid> globalIDs)
```
### ApplyLayout(DiagramLayoutParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Apply a predefined layout on all network diagram elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ApplyLayout(DiagramLayoutParameters layoutParameters)
```
### ApplyLayout(DiagramLayoutParameters, DiagramElementObjectIDs)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Apply a predefined layout on a subset of diagram elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ApplyLayout(DiagramLayoutParameters layoutParameters, DiagramElementObjectIDs subset)
```
### ApplyLayout(DiagramLayoutParameters, DiagramElementObjectIDs, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Apply a predefined layout on a subset of diagram elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ApplyLayout(DiagramLayoutParameters layoutParameters, DiagramElementObjectIDs subset, ServiceSynchronizationType serviceSynchronizationType)
```
### ApplyLayout(DiagramLayoutParameters, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Apply a predefined layout on all network diagram elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ApplyLayout(DiagramLayoutParameters layoutParameters, ServiceSynchronizationType serviceSynchronizationType)
```
### ApplyTemplateLayouts()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Applies template layouts to the network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ApplyTemplateLayouts()
```
### ClearDiagramElementInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Clear elements info of this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearDiagramElementInfo()
```
### Delete()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Deletes this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Delete()
```
### DiagramManager

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramManager" data-throw-if-not-resolved="false"></xref> of this network diagram.</p>


```csharp
public DiagramManager DiagramManager { get; }
```
### DiagramTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref> of this network diagram.</p>


```csharp
public DiagramTemplate DiagramTemplate { get; }
```
### Extend(NetworkDiagramExtendType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Extends this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Extend(NetworkDiagramExtendType extendType)
```
### Extend(NetworkDiagramExtendType, IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Extends this network diagram starting from a list of input feature global IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Extend(NetworkDiagramExtendType extendType, IEnumerable<Guid> globalIDs)
```
### FindDiagramFeatures(FindDiagramFeatureQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.Data.NetworkDiagrams.FindResultItem" data-throw-if-not-resolved="false"></xref>s
corresponding to the input list of network feature global IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<FindResultItem> FindDiagramFeatures(FindDiagramFeatureQuery query)
```
### FindInitialNetworkRows()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.Data.NetworkDiagrams.FindResultItem" data-throw-if-not-resolved="false"></xref>s
corresponding to the initial list of network rows used to generate the diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<FindResultItem> FindInitialNetworkRows()
```
### FindNetworkRows(FindNetworkRowQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.Data.NetworkDiagrams.FindResultItem" data-throw-if-not-resolved="false"></xref>s
corresponding to the input list of diagram feature global IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<FindResultItem> FindNetworkRows(FindNetworkRowQuery query)
```
### GetAggregations()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramAggregation" data-throw-if-not-resolved="false"></xref>s contained in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<DiagramAggregation> GetAggregations()
```
### GetConsistencyState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramConsistencyState" data-throw-if-not-resolved="false"></xref> of the network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagramConsistencyState GetConsistencyState()
```
### GetContent(bool, bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Returns diagram information and content as a JSON string.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetContent(bool addDiagramInfo, bool addGeometries, bool addAttributes, bool addAggregations)
```
### GetContent(bool, bool, bool, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Returns diagram information and content as a JSON string.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetContent(bool addDiagramInfo, bool addGeometries, bool addAttributes, bool addAggregations, bool useCodedValueNames)
```
### GetDiagramElementInfo(DiagramElementFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Get elements info of this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IList<DiagramElementInfo> GetDiagramElementInfo(DiagramElementFilter filter)
```
### GetDiagramElementInfo(DiagramElementSelection)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Get elements info of this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IList<DiagramElementInfo> GetDiagramElementInfo(DiagramElementSelection selection)
```
### GetDiagramInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Get <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo" data-throw-if-not-resolved="false"></xref> from the network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagramInfo GetDiagramInfo()
```
### GetFeatureAttributes(DiagramElementFilter, string[], bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Get feature attributes of elements and aggregations of this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramElementsAttributes GetFeatureAttributes(DiagramElementFilter filter, string[] attributeNames, bool addAggregatedElementValues, bool useCodedValueNames)
```
### GetFeatureAttributes(DiagramElementSelection, string[], bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Get feature attributes of elements and aggregations of this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramElementsAttributes GetFeatureAttributes(DiagramElementSelection selection, string[] attributeNames, bool addAggregatedElementValues, bool useCodedValueNames)
```
### GetFlags(NetworkDiagramFlagType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramFlag" data-throw-if-not-resolved="false"></xref>s of the flags contained in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<DiagramFlag> GetFlags(NetworkDiagramFlagType flagType)
```
### GetSourceAttributeValues(string, string[], bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Returns diagram features source attribute values as a JSON string.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetSourceAttributeValues(string sourceName, string[] attributeNames, bool useCodedValueNames)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Gets the name of this network diagram.</p>


```csharp
public string Name { get; }
```
### Overwrite(IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Overwrites this network diagram using a list of geographic features (specified by Global ID).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Overwrite(IEnumerable<Guid> globalIDs)
```
### QueryDiagramElements(DiagramElementQueryByElementTypes)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Query diagram elements contained in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramElementQueryResult QueryDiagramElements(DiagramElementQueryByElementTypes query)
```
### QueryDiagramElements(DiagramElementQueryByExtent)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Query diagram elements contained in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramElementQueryResult QueryDiagramElements(DiagramElementQueryByExtent query)
```
### QueryDiagramElements(DiagramElementQueryByObjectIDs)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Query diagram elements contained in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramElementQueryResult QueryDiagramElements(DiagramElementQueryByObjectIDs query)
```
### RemoveFlag(NetworkDiagramFlagType, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Removes a flag in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveFlag(NetworkDiagramFlagType flagType, int diagramElementID)
```
### RemoveFlags(NetworkDiagramFlagType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Removes the flags in this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveFlags(NetworkDiagramFlagType flagType)
```
### SaveLayout(NetworkDiagramSubset, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Saves the layout of diagram elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveLayout(NetworkDiagramSubset subset, bool keepVertices)
```
### SetDiagramElementInfo(DiagramElementFilter, IList&lt;DiagramElementInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Set junctions info of this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDiagramElementInfo(DiagramElementFilter filter, IList<DiagramElementInfo> diagramElementsInfo)
```
### Store(string, NetworkDiagramAccessType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Stores this network diagram with a given name, access type and tag.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Store(string name, NetworkDiagramAccessType accessType, string tag)
```
### Update()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.yml" sourcestartlinenumber="1">Updates this network diagram.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Update()
```


