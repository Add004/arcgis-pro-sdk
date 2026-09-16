# RelationshipClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Represents an association between two tables in a geodatabase.</p>


## Object Signature

```csharp
public class RelationshipClass : Dataset, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">The primary difference between a RelationshipClass and <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref> is that a
RelationshipClass does not have an intermediate table.</p>


## Members

### CreateRelationship(Row, Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Relationship CreateRelationship(Row originRow, Row destinationRow)
```
### DeleteRelationship(Row, Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Removes a relationship between the two specified rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteRelationship(Row originRow, Row destinationRow)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.RelationshipClassDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RelationshipClassDefinition GetDefinition()
```
### GetFeatureDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FeatureDataset" data-throw-if-not-resolved="false"></xref> in which this relationship class is contained.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public FeatureDataset GetFeatureDataset()
```
### GetID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Gets the ID associated with this relationship class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetID()
```
### GetRowsRelatedToDestinationRows(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Gets the rows from the origin table that are related to the destination row object IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Row> GetRowsRelatedToDestinationRows(IEnumerable<long> destinationObjectIDs)
```
### GetRowsRelatedToOriginRows(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Gets the rows from the destination table that are related to the origin row object IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Row> GetRowsRelatedToOriginRows(IEnumerable<long> originObjectIDs)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```


