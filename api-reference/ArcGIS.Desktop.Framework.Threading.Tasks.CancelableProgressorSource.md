# CancelableProgressorSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Class used to configure progress and cancelation during task execution.</p>


## Object Signature

```csharp
public sealed class CancelableProgressorSource : ProgressorSourceBase, IDisposable
```


## Members

### CancelableProgressorSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Creates CancelableProgressorSource.  No progress dialog will be displayed.</p>


```csharp
public CancelableProgressorSource()
```
### CancelableProgressorSource(ProgressDialog)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Creates CancelableProgressorSource with a specified progress dialog.</p>


```csharp
public CancelableProgressorSource(ProgressDialog progDlg)
```
### CancelableProgressorSource(Action&lt;CancelableProgressor&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Creates CancelableProgressorSource with a custom progress update delegate.  No progress dialog will be displayed.</p>


```csharp
public CancelableProgressorSource(Action<CancelableProgressor> callback)
```
### CancelableProgressorSource(string, string, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Creates ProgressorSource with a simple progress dialog.
Set delayedShow to true for short running operations.</p>


```csharp
public CancelableProgressorSource(string message, string cancelMessage, bool delayedShow = false)
```
### CancellationTokenSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Gets the cancellation configuration object associated with this progressor.</p>


```csharp
public CancellationTokenSource CancellationTokenSource { get; }
```
### Progressor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressorSource.yml" sourcestartlinenumber="1">Gets the progressor object.</p>


```csharp
public CancelableProgressor Progressor { get; }
```


