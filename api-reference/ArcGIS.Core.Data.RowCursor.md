# RowCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RowCursor.yml" sourcestartlinenumber="1">Represents a cursor from a geodatabase table.</p>


## Object Signature

```csharp
public sealed class RowCursor : CoreObjectsBase, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RowCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.RowCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Row Current { get; }
```
### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RowCursor.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RowCursor.yml" sourcestartlinenumber="1">Gets the readonly list of <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>s present in the cursor.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RowCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.RowCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```


