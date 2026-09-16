# CancelableProgressor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor.yml" sourcestartlinenumber="1">Indicates the progress of an operation that is cancelable.</p>


## Object Signature

```csharp
public class CancelableProgressor : Progressor
```


## Members

### CancellationToken

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor.yml" sourcestartlinenumber="1">Gets the cancellation token associated with the progressor.</p>


```csharp
public CancellationToken CancellationToken { get; }
```
### None

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor.yml" sourcestartlinenumber="1">Gets an empty CancelableProgressor which does nothing.</p>


```csharp
public static CancelableProgressor None { get; }
```


