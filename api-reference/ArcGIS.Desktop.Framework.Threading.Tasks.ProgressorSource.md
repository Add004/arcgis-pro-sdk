# ProgressorSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressorSource.yml" sourcestartlinenumber="1">Class used to configure progress during task execution.</p>


## Object Signature

```csharp
public class ProgressorSource : ProgressorSourceBase, IDisposable
```


## Members

### ProgressorSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressorSource.yml" sourcestartlinenumber="1">Creates ProgressorSource.  No progress dialog will be displayed.</p>


```csharp
public ProgressorSource()
```
### ProgressorSource(ProgressDialog)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressorSource.yml" sourcestartlinenumber="1">Creates ProgressorSource with a specified progress dialog.</p>


```csharp
public ProgressorSource(ProgressDialog progDlg)
```
### ProgressorSource(Action&lt;Progressor&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressorSource.yml" sourcestartlinenumber="1">Creates ProgressorSource with a custom progress update delegate.  No progress dialog will be shown.</p>


```csharp
public ProgressorSource(Action<Progressor> callback)
```
### ProgressorSource(string, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressorSource.yml" sourcestartlinenumber="1">Creates ProgressorSource with a simple progress dialog.
Set delayedShow to true for short running operations.</p>


```csharp
public ProgressorSource(string message, bool delayedShow = false)
```
### Progressor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressorSource.yml" sourcestartlinenumber="1">Gets the progressor object.</p>


```csharp
public Progressor Progressor { get; }
```


