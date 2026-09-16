# SequencedEdgeParcelParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.SequencedEdgeParcelParams.yml" sourcestartlinenumber="1">The sequenced edge parcel params that define the behavior of GetSequencedParcelEdgeInfoAsync.</p>


## Object Signature

```csharp
public sealed class SequencedEdgeParcelParams
```


## Members

### SequencedEdgeParcelParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.SequencedEdgeParcelParams.yml" sourcestartlinenumber="1">The sequenced edge parcel params that define the behavior of GetSequencedParcelEdgeInfoAsync.</p>


```csharp
public SequencedEdgeParcelParams()
```
### EdgeRelationshipFilter

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.SequencedEdgeParcelParams.yml" sourcestartlinenumber="1">The line-to-edge relationships used to filter the results to get lines only with those edge relationships specified in the enumeration.</p>


```csharp
public ParcelLineToEdgeRelationship EdgeRelationshipFilter
```
### LineToEdgeMatchTolerance

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.SequencedEdgeParcelParams.yml" sourcestartlinenumber="1">The tolerance used for matching lines to parcel polygon edges. It is the maximum separation allowed for them to be considered coincident.</p>


```csharp
public double LineToEdgeMatchTolerance
```
### OffsetTolerance

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.SequencedEdgeParcelParams.yml" sourcestartlinenumber="1">The offset tolerance used to define tangents for detecting edges for parcel polygon segments.</p>


```csharp
public double OffsetTolerance
```


