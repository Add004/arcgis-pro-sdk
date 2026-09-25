# DelayedInvoker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.DelayedInvoker.yml" sourcestartlinenumber="1">Utility class used to delay action within methods that are called at high frequencies until
the call has not been called for at least the specified interval.</p>


## Object Signature

```csharp
public class DelayedInvoker
```


## Members

### DelayedInvoker(int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.DelayedInvoker.yml" sourcestartlinenumber="1">Creates a new DelayedInvoker instance.</p>


```csharp
public DelayedInvoker(int delay = 200)
```
### DelayedInvoker(int, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.DelayedInvoker.yml" sourcestartlinenumber="1">Creates a new DelayedInvoker instance.</p>


```csharp
public DelayedInvoker(int delay, int maxInvokeCount)
```
### Invoke(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.DelayedInvoker.yml" sourcestartlinenumber="1">The method to execute when the delay elapses.</p>


```csharp
public Task Invoke(Action action)
```
### InvokeTask(Func&lt;Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.DelayedInvoker.yml" sourcestartlinenumber="1">The method to execute when the delay elapses.</p>


```csharp
public Task InvokeTask(Func<Task> function)
```


