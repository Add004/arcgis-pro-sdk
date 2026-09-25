# ParcelEdge

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdge.yml" sourcestartlinenumber="1">ParcelEdge represents a set of line properties that define how it is related to a parcel edge.</p>


## Object Signature

```csharp
public sealed class ParcelEdge
```


## Members

### EdgeGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdge.yml" sourcestartlinenumber="1">Gets the edge polyline.</p>


```csharp
public Polyline EdgeGeometry { get; }
```
### EdgeID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdge.yml" sourcestartlinenumber="1">Gets the ID for this edge.</p>


```csharp
public int EdgeID { get; }
```
### Lines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelEdge.yml" sourcestartlinenumber="1">Gets the ParcelLineInfo list for the edge.</p>


```csharp
public IReadOnlyList<ParcelLineInfo> Lines { get; }
```


