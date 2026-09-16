# BackgroundProgressor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Core.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Class used to retrieve the status and progress of a cancelable operation.</p>


## Object Signature

```csharp
public class BackgroundProgressor
```


## Members

### CancelToken

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Returns the Cancelation Token of the progressor registered
on the calling thread.</p>


```csharp
public CancellationToken CancelToken { get; }
```
### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Returns the Progressor associated with the Task currently running on the calling thread.
Returns null if not called on one of the threads in the pool.</p>


```csharp
public static BackgroundProgressor Current { get; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Gets or Sets the maximum range of the progress meter displayed in the progress dialog.</p>


```csharp
public uint Max { get; set; }
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Gets or Sets message of the progress dialog.</p>


```csharp
public string Message { get; set; }
```
### None

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Returns an empty Progressor which does nothing.</p>


```csharp
public static BackgroundProgressor None { get; }
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Gets or Sets the status displayed in the progress dialog.</p>


```csharp
public string Status { get; set; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressor.yml" sourcestartlinenumber="1">Gets or Sets the position of the progress meter displayed in the progress dialog.</p>


```csharp
public uint Value { get; set; }
```


