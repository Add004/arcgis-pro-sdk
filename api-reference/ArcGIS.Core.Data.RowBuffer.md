# RowBuffer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RowBuffer.yml" sourcestartlinenumber="1">Represents a row buffer that can be used with <xref href="ArcGIS.Core.Data.Table.CreateRow(ArcGIS.Core.Data.RowBuffer)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class RowBuffer : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.RowBuffer.yml" sourcestartlinenumber="1">A row buffer is an in memory representation of the row that can be used to set field values before creating the row in the table.
<xref href="ArcGIS.Core.Data.Table.CreateRow(ArcGIS.Core.Data.RowBuffer)" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RowBuffer.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RowBuffer.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing the fields of the RowBuffer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RowBuffer.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its index position.
This indexer must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RowBuffer.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its attribute name or alias name.
This indexer must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[string fieldName] { get; set; }
```


