# BackgroundProgressorSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Core.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Class used to configure progress and cancelation during task execution.</p>


## Object Signature

```csharp
public class BackgroundProgressorSource : IDisposable
```


## Members

### BackgroundProgressorSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Creates BackgroundProgressorSource.</p>


```csharp
public BackgroundProgressorSource()
```
### BackgroundProgressorSource(Action&lt;BackgroundProgressor&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Creates BackgroundProgressorSource with a custom progress update delegate.</p>


```csharp
public BackgroundProgressorSource(Action<BackgroundProgressor> callback)
```
### CancellationTokenSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Returns the cancellation configuration object associated with this progressor.</p>


```csharp
public CancellationTokenSource CancellationTokenSource { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Dispose implementation</p>


```csharp
public void Dispose()
```
### Dispose(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Releases this object's unmanaged resources.</p>


```csharp
protected virtual void Dispose(bool disposing)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Gets or sets the progress maximum value.</p>


```csharp
public uint Max { get; set; }
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Gets or sets the message.</p>


```csharp
public string Message { get; set; }
```
### Progressor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Returns the progressor object.</p>


```csharp
public BackgroundProgressor Progressor { get; }
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Gets or sets the status.</p>


```csharp
public string Status { get; set; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.Threading.Tasks.BackgroundProgressorSource.yml" sourcestartlinenumber="1">Gets or sets the progress value.</p>


```csharp
public uint Value { get; set; }
```


