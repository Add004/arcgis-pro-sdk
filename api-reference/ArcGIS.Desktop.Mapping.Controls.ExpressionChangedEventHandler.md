# ExpressionChangedEventHandler

- Type: delegate
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ExpressionChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the ExpressionChanged event of the QueryBuilderControl.</p>


## Object Signature

```csharp
public delegate void ExpressionChangedEventHandler(object sender, ExpressionChangedEventArgs args)
```


## Members

### ExpressionChangedEventHandler(object, nint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ExpressionChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the ExpressionChanged event of the QueryBuilderControl.</p>


```csharp
public ExpressionChangedEventHandler(object @object, nint method)
```
### BeginInvoke(object, ExpressionChangedEventArgs, AsyncCallback, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ExpressionChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the ExpressionChanged event of the QueryBuilderControl.</p>


```csharp
public virtual IAsyncResult BeginInvoke(object sender, ExpressionChangedEventArgs args, AsyncCallback callback, object @object)
```
### EndInvoke(IAsyncResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ExpressionChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the ExpressionChanged event of the QueryBuilderControl.</p>


```csharp
public virtual void EndInvoke(IAsyncResult result)
```
### Invoke(object, ExpressionChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ExpressionChangedEventHandler.yml" sourcestartlinenumber="1">Callback for the ExpressionChanged event of the QueryBuilderControl.</p>


```csharp
public virtual void Invoke(object sender, ExpressionChangedEventArgs args)
```


