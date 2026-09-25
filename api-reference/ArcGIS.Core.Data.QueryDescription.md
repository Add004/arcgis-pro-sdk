# QueryDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">A <code>QueryDescription</code> object fully describes how a <b>single table</b> in a database or a <b>query layer</b> that<br>
is created from one or more database tables (specified by a valid SQL SELECT statement) should be represented as a
<xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> if the table is spatially enabled.</p>
<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="5"><xref href="ArcGIS.Core.Data.Database.GetQueryDescription(System.String)" data-throw-if-not-resolved="false"></xref><xref href="ArcGIS.Core.Data.Database.GetQueryDescription(System.String%2cSystem.String)" data-throw-if-not-resolved="false"></xref><xref href="ArcGIS.Core.Data.Database.GetQueryDescription(ArcGIS.Core.Data.Table)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class QueryDescription : CoreObjectsBase, IDisposable
```


## Members

### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing the fields of the underlying table(s).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetObjectIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the name of the ObjectID field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetObjectIDField()
```
### GetObjectIDFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets a comma-separated unique key field(s) that fulfill the role of a table's objectID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetObjectIDFields()
```
### GetQueryStatement()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the SQL SELECT statement that governs how a <b>query layer</b> or <b>single table</b> is created.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetQueryStatement()
```
### GetSRID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the spatial reference ID of the resultset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetSRID()
```
### GetShapeField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the name of the geometry column if present.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetShapeField()
```
### GetShapeType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the geometry type on the spatial column of the underlying <b>single table</b> or <b>query layer</b> if present.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GeometryType GetShapeType()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the spatial reference.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### IsObjectIDMappedColumnRequired()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Indicates if a virtual ObjectID column is required.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsObjectIDMappedColumnRequired()
```
### IsQueryLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Indicates whether this instance of <b>QueryDescription</b> represents a <b>query layer</b> or a <b>single table</b>.
If <b>true</b>, it is a <b>query layer</b> .  Otherwise, it is a <b>single table</b>.</p>


```csharp
public bool IsQueryLayer { get; }
```
### IsSpatialQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Indicates if the query resultset is spatial.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsSpatialQuery()
```
### QueryLayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the <code>user-specified</code> name of the <b>query layer</b> being represented by this instance of <b>QueryDescription</b>.</p>


```csharp
public string QueryLayerName { get; }
```
### SetObjectIDFields(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Sets the unique key field(s) that fulfill the role of a table's objectID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetObjectIDFields(string objectIDFields)
```
### SetSRID(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Sets the spatial reference ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSRID(string srid)
```
### SetShapeType(GeometryType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Sets the geometry type on the spatial column of the underlying <b>single table</b> or <b>query layer</b> if present.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShapeType(GeometryType shapeType)
```
### SetSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Sets the spatial reference.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSpatialReference(SpatialReference spatialReference)
```
### TableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the fully qualified name of the underlying database table being represented by this instance of <b>QueryDescription</b>.<br>
Depending on the database platform, the fully qualified name consists of either &quot;databaseName.ownerName.tableName&quot; (e.g., SQL Server)
or &quot;ownerName.tableName&quot; (e.g., Oracle).</p>


```csharp
public string TableName { get; }
```
### UniqueQueryLayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDescription.yml" sourcestartlinenumber="1">Gets the system-generated <code>unique</code> name of the <b>query layer</b> being represented by this instance of <b>QueryDescription</b>.</p>


```csharp
public string UniqueQueryLayerName { get; }
```


