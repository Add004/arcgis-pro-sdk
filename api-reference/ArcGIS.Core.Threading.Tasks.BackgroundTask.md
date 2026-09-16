# BackgroundTask

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Core.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Static class used to perform asynchronous operations within the background thread pool.</p>


## Object Signature

```csharp
public static class BackgroundTask
```


## Members

### Busy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Returns true if there is at least one operation executing in the thread pool.</p>


```csharp
public static bool Busy { get; }
```
### PoolSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Returns the number of threads within the background thread pool.</p>


```csharp
public static uint PoolSize { get; }
```
### Run(TaskPriority, Action, BackgroundProgressor, TaskContinuationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Queue a new task to the background thread pool using the specified progressor.</p>


```csharp
public static Task Run(TaskPriority priority, Action action, BackgroundProgressor progressor, TaskContinuationOptions options = TaskContinuationOptions.None)
```
### Run(Action, BackgroundProgressor, TaskContinuationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Queue a new task to the background thread pool using the specified progressor.</p>


```csharp
public static Task Run(Action action, BackgroundProgressor progressor, TaskContinuationOptions options = TaskContinuationOptions.None)
```
### Run&lt;T&gt;(TaskPriority, Func&lt;T&gt;, BackgroundProgressor, TaskContinuationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Queue a new task to the background thread pool using the specified progressor.</p>


```csharp
public static Task<T> Run<T>(TaskPriority priority, Func<T> function, BackgroundProgressor progressor, TaskContinuationOptions options = TaskContinuationOptions.None)
```
### Run&lt;T&gt;(Func&lt;T&gt;, BackgroundProgressor, TaskContinuationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundTask.yml" sourcestartlinenumber="1">Queue a new task to the background thread pool using the specified progressor.</p>


```csharp
public static Task<T> Run<T>(Func<T> function, BackgroundProgressor progressor, TaskContinuationOptions options = TaskContinuationOptions.None)
```


