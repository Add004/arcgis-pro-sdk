# QueuedTask

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Static class used to perform asynchronous operations on the foreground worker thread.</p>


## Object Signature

```csharp
public static class QueuedTask
```


## Members

### Busy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Gets a boolean value of True if the worker thread is busy.</p>


```csharp
public static bool Busy { get; }
```
### OnGUI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Gets a boolean value of True if called from the GUI thread.</p>


```csharp
public static bool OnGUI { get; }
```
### OnWorker

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Gets a boolean value of True if called from the worker thread.</p>


```csharp
public static bool OnWorker { get; }
```
### Run(Action, CancelableProgressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new cancelable task to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task Run(Action action, CancelableProgressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run(Action, Progressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task Run(Action action, Progressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run(Action, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task to the framework dispatcher thread.</p>


```csharp
public static Task Run(Action action, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run(Func&lt;Task&gt;, CancelableProgressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new cancelable task to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task Run(Func<Task> function, CancelableProgressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run(Func&lt;Task&gt;, Progressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task Run(Func<Task> function, Progressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run(Func&lt;Task&gt;, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task to the framework dispatcher thread.</p>


```csharp
public static Task Run(Func<Task> function, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run&lt;T&gt;(Func&lt;Task&lt;T&gt;&gt;, CancelableProgressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new cancelable task of type T to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task<T> Run<T>(Func<Task<T>> function, CancelableProgressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run&lt;T&gt;(Func&lt;Task&lt;T&gt;&gt;, Progressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task of type T to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task<T> Run<T>(Func<Task<T>> function, Progressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run&lt;T&gt;(Func&lt;Task&lt;T&gt;&gt;, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task of type T to the framework dispatcher.</p>


```csharp
public static Task<T> Run<T>(Func<Task<T>> function, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run&lt;T&gt;(Func&lt;T&gt;, CancelableProgressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new cancelable task of type T to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task<T> Run<T>(Func<T> function, CancelableProgressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run&lt;T&gt;(Func&lt;T&gt;, Progressor, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task of type T to the framework dispatcher thread using the specified progressor.</p>


```csharp
public static Task<T> Run<T>(Func<T> function, Progressor progressor, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Run&lt;T&gt;(Func&lt;T&gt;, TaskCreationOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Queue a new task of type T to the framework dispatcher.</p>


```csharp
public static Task<T> Run<T>(Func<T> function, TaskCreationOptions creationOptions = TaskCreationOptions.None)
```
### Shutdown(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Call at application exit to shutdown the worker thread.</p>


```csharp
public static bool Shutdown(int timeout)
```
### UIScheduler

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.QueuedTask.yml" sourcestartlinenumber="1">Gets the TaskScheduler associated with the GUI thread; can be used to dispatch delegates that need to run on the user interface thread.</p>


```csharp
public static TaskScheduler UIScheduler { get; }
```


