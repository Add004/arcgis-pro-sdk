# AttributedRelationshipClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Represents an association between two tables in a geodatabase on which additional information is stored in an intermediate table.</p>


## Object Signature

```csharp
public sealed class AttributedRelationshipClass : RelationshipClass, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">By default, the intermediate table has three system-generated fields whose name can be retrieved using
<xref href="ArcGIS.Core.Data.AttributedRelationshipClassDefinition.GetObjectIDField" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.AttributedRelationshipClassDefinition.GetDestinationKeyField" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Data.AttributedRelationshipClassDefinition.GetDestinationForeignKeyField" data-throw-if-not-resolved="false"></xref>, respectively.  However, the intermediate
table may have additional user-defined attributes defined at the moment the AttributedRelationshipClass is created.  An AttributedRelationshipClass
is always created for relationship classes whose cardinality is many-to-many (<xref href="ArcGIS.Core.Data.RelationshipCardinality.ManyToMany" data-throw-if-not-resolved="false"></xref>)
regardless of whether they have additional user-defined attributes.</p>


## Members

### CreateRelationship(Row, Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified rows and/or features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributedRelationship CreateRelationship(Row originRow, Row destinationRow)
```
### CreateRelationship(Row, Row, RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Creates a new relationship between the two specified rows and/or features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributedRelationship CreateRelationship(Row originRow, Row destinationRow, RowBuffer attributes)
```
### CreateRowBuffer()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Creates a new row buffer instance in memory.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowBuffer CreateRowBuffer()
```
### GetArchiveTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Gets the archive table associated with this attributed relationship class's intermediate table if it is archived-enabled.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetArchiveTable()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.AttributedRelationshipClassDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributedRelationshipClassDefinition GetDefinition()
```
### GetRelationshipsForDestinationRows(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Gets a list of all the <xref href="ArcGIS.Core.Data.AttributedRelationship" data-throw-if-not-resolved="false"></xref> that the destination rows with the specified
<code class="paramref">destinationObjectIDs</code> participate in.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AttributedRelationship> GetRelationshipsForDestinationRows(IEnumerable<long> destinationObjectIDs)
```
### GetRelationshipsForOriginRows(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Gets a list of all the <xref href="ArcGIS.Core.Data.AttributedRelationship" data-throw-if-not-resolved="false"></xref> that the origin rows with the specified
<code class="paramref">originObjectIDs</code> participate in.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AttributedRelationship> GetRelationshipsForOriginRows(IEnumerable<long> originObjectIDs)
```
### IsArchiveEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Gets a value indicating whether this attributed relationship class's intermediate table is archive-enabled.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsArchiveEnabled()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```


