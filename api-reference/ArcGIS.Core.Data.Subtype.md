# Subtype

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Subtype.yml" sourcestartlinenumber="1">Represents a subset of features in a feature class or rows in a table that share the same attributes.</p>


## Object Signature

```csharp
public sealed class Subtype : CoreObjectsBase, IDisposable
```


## Members

### GetCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Subtype.yml" sourcestartlinenumber="1">Gets the code value of the subtype.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetCode()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Subtype.yml" sourcestartlinenumber="1">Gets the name value of the subtype.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```


