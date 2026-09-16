# DifferenceCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DifferenceCursor.yml" sourcestartlinenumber="1">Represents a difference cursor to retrieve rows that are different between two versions (either transactional or historical) based on the
specified <xref href="ArcGIS.Core.Data.DifferenceType" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class DifferenceCursor : CoreObjectsBase, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DifferenceCursor.yml" sourcestartlinenumber="1">Gets the current difference <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.DifferenceCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Row Current { get; }
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DifferenceCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.DifferenceCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DifferenceCursor.yml" sourcestartlinenumber="1">Gets the object ID of current difference <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.DifferenceCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public long ObjectID { get; }
```


