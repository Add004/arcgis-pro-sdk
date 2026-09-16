# GPToolExecuteEventHandler

- Type: delegate
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolExecuteEventHandler.yml" sourcestartlinenumber="1">Callback delegate, pass a lambda call to <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public delegate void GPToolExecuteEventHandler(string eventName, object o)
```


## Members

### GPToolExecuteEventHandler(object, nint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolExecuteEventHandler.yml" sourcestartlinenumber="1">Callback delegate, pass a lambda call to <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public GPToolExecuteEventHandler(object @object, nint method)
```
### BeginInvoke(string, object, AsyncCallback, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolExecuteEventHandler.yml" sourcestartlinenumber="1">Callback delegate, pass a lambda call to <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual IAsyncResult BeginInvoke(string eventName, object o, AsyncCallback callback, object @object)
```
### EndInvoke(IAsyncResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolExecuteEventHandler.yml" sourcestartlinenumber="1">Callback delegate, pass a lambda call to <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual void EndInvoke(IAsyncResult result)
```
### Invoke(string, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolExecuteEventHandler.yml" sourcestartlinenumber="1">Callback delegate, pass a lambda call to <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual void Invoke(string eventName, object o)
```


