# QueuedWorker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Hosting.html">Hosting</a>.<a class="xref" href="ArcGIS.Core.Hosting.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Core.Hosting.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.CoreHost.dll

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Class provides a Task based execution model around a Core.Objects compatible worker thread.</p>


## Object Signature

```csharp
public static class QueuedWorker
```


## Members

### Busy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Returns True if the worker thread is busy.</p>


```csharp
public static bool Busy { get; }
```
### OnWorker

- Kind: property

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Returns True if called from the worker thread.</p>


```csharp
public static bool OnWorker { get; }
```
### Run(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Queues a task to the queued worker thread.</p>


```csharp
public static Task Run(Action action)
```
### Run(Action, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Queues a task to the queued worker thread.</p>


```csharp
public static Task Run(Action action, CancellationToken cancellationToken)
```
### Run&lt;T&gt;(Func&lt;T&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Queues a task to the queued worker thread.</p>


```csharp
public static Task<T> Run<T>(Func<T> function)
```
### Run&lt;T&gt;(Func&lt;T&gt;, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Queues a task to the queued worker thread.</p>


```csharp
public static Task<T> Run<T>(Func<T> function, CancellationToken cancellationToken)
```
### Shutdown(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Threading.Tasks.QueuedWorker.yml" sourcestartlinenumber="1">Method should be called when the host application is shutting down.</p>


```csharp
public static bool Shutdown(int timeout)
```


