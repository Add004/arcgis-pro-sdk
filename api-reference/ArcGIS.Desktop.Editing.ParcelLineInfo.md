# ParcelLineInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">The ParcelLineInfo class represents a set of line properties that define how it is related to a parcel edge.</p>


## Object Signature

```csharp
public sealed class ParcelLineInfo
```


## Members

### EdgeID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the ID for the edge associated with this line. Multiple returned for natural boundaries.</p>


```csharp
public IReadOnlyList<int> EdgeID { get; }
```
### EdgeRelationship

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the evaluated enum value for the line-to-edge relationships.</p>


```csharp
public ParcelLineToEdgeRelationship EdgeRelationship { get; }
```
### EndPositionOnParcelEdge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the proportional position on the parcel edge for the end vertex of the line feature.</p>


```csharp
public double EndPositionOnParcelEdge { get; }
```
### FeatureAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the parcel line feature attributes.</p>


```csharp
public ReadOnlyDictionary<string, object> FeatureAttributes { get; }
```
### FeatureGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the parcel line feature polyline.</p>


```csharp
public Polyline FeatureGeometry { get; }
```
### FromPointObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the line’s from-point oid. Multiple returned if coincident point features are found.</p>


```csharp
public IReadOnlyList<long> FromPointObjectID { get; }
```
### HasNextLineConnectivity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets whether the parcel line has any other next line connected by a shared end vertex.
Next line means on the clockwise end in the edge sequence.</p>


```csharp
public bool HasNextLineConnectivity { get; }
```
### HasPreviousLineConnectivity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets whether the parcel line has any other previous line connected by a shared end vertex.
Previous line means on the counter-clockwise end in the edge sequence.</p>


```csharp
public bool HasPreviousLineConnectivity { get; }
```
### IsClosing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets whether the parcel line is a closing line, connected to the starting line feature.</p>


```csharp
public bool IsClosing { get; }
```
### IsReversed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets whether the parcel line is oriented in the same direction as the polygon edges.</p>


```csharp
public bool IsReversed { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the line feature’s oid.</p>


```csharp
public long ObjectID { get; }
```
### RecordGUID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the line’s record guid.</p>


```csharp
public Guid RecordGUID { get; }
```
### StartPositionOnParcelEdge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the proportional position on the parcel edge for the start vertex of the line feature.</p>


```csharp
public double StartPositionOnParcelEdge { get; }
```
### ToPointObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParcelLineInfo.yml" sourcestartlinenumber="1">Gets the line’s to-point oid. Multiple returned if coincident point features are found.</p>


```csharp
public IReadOnlyList<long> ToPointObjectID { get; }
```


