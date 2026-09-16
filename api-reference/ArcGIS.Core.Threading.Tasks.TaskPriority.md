# TaskPriority

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Core.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.TaskPriority.yml" sourcestartlinenumber="1">Used to execute operations on the shared background thread pool.</p>


## Object Signature

```csharp
public enum TaskPriority
```


## Members

### high

- Kind: field

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.TaskPriority.yml" sourcestartlinenumber="1">Use only for short duration operations.</p>


```csharp
high = 1
```
### normal

- Kind: field

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.TaskPriority.yml" sourcestartlinenumber="1">Use for potentially long running operations.</p>


```csharp
normal = 0
```
### single

- Kind: field

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.TaskPriority.yml" sourcestartlinenumber="1">Runs operation on a single consistent background thread.  Appropriate for tasks with thread affinity concerns.</p>


```csharp
single = 2
```


