# ParcelEdgeCollection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdgeCollection.yml" sourcestartlinenumber="1">ParcelEdgeCollection represents a collection of parcel edges in a clockwise order.</p>


## Object Signature

```csharp
public sealed class ParcelEdgeCollection
```


## Members

### Edges

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdgeCollection.yml" sourcestartlinenumber="1">Gets the ParcelEdge info in clockwise edge sequence.</p>


```csharp
public IReadOnlyList<ParcelEdge> Edges { get; }
```
### Points

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdgeCollection.yml" sourcestartlinenumber="1">Gets the objectIDs of the point features corresponding with the ends of returned lines.</p>


```csharp
public IReadOnlyList<long> Points { get; }
```


