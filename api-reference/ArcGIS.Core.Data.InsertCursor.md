# InsertCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.InsertCursor.yml" sourcestartlinenumber="1">This class allows users to quickly and efficiently insert rows in a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class InsertCursor : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.InsertCursor.yml" sourcestartlinenumber="1">The InsertCursor class is designed for fast row inserts.  It is guaranteed to provide performance at least as good as calling
<xref href="ArcGIS.Core.Data.Table.CreateRow(ArcGIS.Core.Data.RowBuffer)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Row.Store" data-throw-if-not-resolved="false"></xref> in a loop.  For many tables and feature classes, performance may be significantly
better.
When used in an ArcGIS Pro add-in, insert cursors should be used within an <a href="https://github.com/esri/arcgis-pro-sdk/wiki/ProConcepts-Editing#edit-operation-callback" target="_blank">edit operation callback</a>.
For stand-alone CoreHost applications, insert cursor usage should be enclosed within a call to <xref href="ArcGIS.Core.Data.Geodatabase.ApplyEdits(System.Action)" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Flush()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.InsertCursor.yml" sourcestartlinenumber="1">Write all changes to the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Flush()
```
### Insert(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.InsertCursor.yml" sourcestartlinenumber="1">Inserts a new <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> into the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> with a system-assigned object ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long Insert(RowBuffer rowBuffer)
```


