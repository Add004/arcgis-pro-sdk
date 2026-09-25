# SetOperation

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.SetOperation.yml" sourcestartlinenumber="1">Specifies the operation to be applied to the selections.</p>


## Object Signature

```csharp
public enum SetOperation
```


## Members

### Difference

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SetOperation.yml" sourcestartlinenumber="1">All rows present in the first selection but not present in the second are copied to the output selection. This is a Boolean INHIBITION operation (e.g., C# a.Except(b)).</p>


```csharp
Difference = 3
```
### Intersection

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SetOperation.yml" sourcestartlinenumber="1">All rows present in both input selections are copied to the output selection. Those row IDs present in only one set are discarded. This is a Boolean AND operation.</p>


```csharp
Intersection = 2
```
### SymmetricDifference

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SetOperation.yml" sourcestartlinenumber="1">All rows present in either input selection, but not present in both, are copied to the output selection. This is a Boolean XOR operation.</p>


```csharp
SymmetricDifference = 4
```
### Union

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SetOperation.yml" sourcestartlinenumber="1">All rows present in the first selection and the second selection are copied to the output selection. This is a Boolean OR operation.</p>


```csharp
Union = 1
```


