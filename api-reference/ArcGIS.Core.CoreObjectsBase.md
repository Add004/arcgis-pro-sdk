# CoreObjectsBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CoreObjectsBase.yml" sourcestartlinenumber="1">This is the ultimate base class of all classes that consume unmanaged resources in the ArcGIS Pro API.</p>


## Object Signature

```csharp
public abstract class CoreObjectsBase : IDisposable
```


## Members

### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CoreObjectsBase.yml" sourcestartlinenumber="1">Releases this object's unmanaged resources.</p>


```csharp
public void Dispose()
```
### Handle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CoreObjectsBase.yml" sourcestartlinenumber="1">Gets the opaque handle to the underlying native object.</p>


```csharp
public nint Handle { get; }
```


