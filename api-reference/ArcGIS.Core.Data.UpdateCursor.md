# UpdateCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UpdateCursor.yml" sourcestartlinenumber="1">This class allows users to quickly and efficiently update rows in a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class UpdateCursor : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UpdateCursor.yml" sourcestartlinenumber="1">The UpdateCursor class is designed for fast row updates.  It is guaranteed to provide performance at least as good as calling
<xref href="ArcGIS.Core.Data.Table.CreateRow(ArcGIS.Core.Data.RowBuffer)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Row.Store" data-throw-if-not-resolved="false"></xref> in a loop.  For many tables and feature classes, performance may be significantly
better.
When used in an ArcGIS Pro add-in, update cursors should be used within an <a href="https://github.com/esri/arcgis-pro-sdk/wiki/ProConcepts-Editing#edit-operation-callback" target="_blank">edit operation callback</a>.
For stand-alone CoreHost applications, update cursor usage should be enclosed within a call to <xref href="ArcGIS.Core.Data.Geodatabase.ApplyEdits(System.Action)" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UpdateCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.UpdateCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Row Current { get; }
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UpdateCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.UpdateCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```
### Update(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UpdateCursor.yml" sourcestartlinenumber="1">Updates an existing <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Update(Row row)
```


