# RealtimeRow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Represents a row in a <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref> returned by <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class RealtimeRow : CoreObjectsBase, IDisposable
```


## Members

### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method can be called on any thread.</p>


```csharp
public int FindField(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing the fields of the RealtimeRow.
This method can be called on any thread.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Gets the object ID of the row.
This method can be called on any thread.</p>


```csharp
public long GetObjectID()
```
### GetRowSource()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Returns the source of this real-time row.
This method can be called on any thread.</p>


```csharp
public RealtimeRowSource GetRowSource()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its index position.
This indexer can be called on any thread.</p>


```csharp
public virtual object this[int index] { get; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRow.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its attribute name or alias name.
This indexer can be called on any thread.</p>


```csharp
public object this[string fieldName] { get; }
```


