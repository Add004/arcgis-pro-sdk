# TranslateHResultDelegate

- Type: delegate
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.TranslateHResultDelegate.yml" sourcestartlinenumber="1">For internal use only</p>


## Object Signature

```csharp
public delegate Exception TranslateHResultDelegate(int hresult)
```


## Members

### TranslateHResultDelegate(object, nint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.TranslateHResultDelegate.yml" sourcestartlinenumber="1">For internal use only</p>


```csharp
public TranslateHResultDelegate(object @object, nint method)
```
### BeginInvoke(int, AsyncCallback, object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.TranslateHResultDelegate.yml" sourcestartlinenumber="1">For internal use only</p>


```csharp
public virtual IAsyncResult BeginInvoke(int hresult, AsyncCallback callback, object @object)
```
### EndInvoke(IAsyncResult)

- Kind: method

<p sourcefile="api/ArcGIS.Core.TranslateHResultDelegate.yml" sourcestartlinenumber="1">For internal use only</p>


```csharp
public virtual Exception EndInvoke(IAsyncResult result)
```
### Invoke(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.TranslateHResultDelegate.yml" sourcestartlinenumber="1">For internal use only</p>


```csharp
public virtual Exception Invoke(int hresult)
```


