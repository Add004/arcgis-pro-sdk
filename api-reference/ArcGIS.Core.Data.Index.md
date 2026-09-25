# Index

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Represents an index from a geodatabase table.</p>


## Object Signature

```csharp
public sealed class Index : CoreObjectsBase, IDisposable
```


## Members

### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>s present in the index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Gets the name of the index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### IsAscending()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Indicates if the index is based on ascending order.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsAscending()
```
### IsFullText()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Indicates if the index is a full text index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsFullText()
```
### IsUnique()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Index.yml" sourcestartlinenumber="1">Indicates if the index is unique.  If IsUnique is true, the field the Index was created for must not have duplicate values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsUnique()
```


