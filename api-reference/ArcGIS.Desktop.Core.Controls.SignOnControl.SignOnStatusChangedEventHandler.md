# SignOnControl.SignOnStatusChangedEventHandler

- Type: delegate
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.SignOnStatusChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SignOnStatusChanged event.</p>


## Object Signature

```csharp
public delegate void SignOnControl.SignOnStatusChangedEventHandler(object sender, SignOnStatusChangedEventArgs args)
```


## Members

### SignOnStatusChangedEventHandler(object, nint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.SignOnStatusChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SignOnStatusChanged event.</p>


```csharp
public SignOnStatusChangedEventHandler(object @object, nint method)
```
### BeginInvoke(object, SignOnStatusChangedEventArgs, AsyncCallback, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.SignOnStatusChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SignOnStatusChanged event.</p>


```csharp
public virtual IAsyncResult BeginInvoke(object sender, SignOnStatusChangedEventArgs args, AsyncCallback callback, object @object)
```
### EndInvoke(IAsyncResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.SignOnStatusChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SignOnStatusChanged event.</p>


```csharp
public virtual void EndInvoke(IAsyncResult result)
```
### Invoke(object, SignOnStatusChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.SignOnStatusChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the SignOnStatusChanged event.</p>


```csharp
public virtual void Invoke(object sender, SignOnStatusChangedEventArgs args)
```


