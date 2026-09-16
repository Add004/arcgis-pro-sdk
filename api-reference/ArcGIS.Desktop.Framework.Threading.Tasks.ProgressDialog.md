# ProgressDialog

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Provides visual feedback during long operations</p>


## Object Signature

```csharp
public class ProgressDialog : IDisposable
```


## Members

### ProgressDialog(string, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Creates a simple progress dialog.</p>


```csharp
public ProgressDialog(string message, bool delayedShow = false)
```
### ProgressDialog(string, string, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Creates a cancelable progress dialog.</p>


```csharp
public ProgressDialog(string message, string cancelMessage, bool delayedShow = false)
```
### ProgressDialog(string, string, uint, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Creates a cancelable progress dialog with the specified number of steps.</p>


```csharp
public ProgressDialog(string message, string cancelMessage, uint steps, bool delayedShow = false)
```
### ProgressDialog(string, uint, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Creates a progress dialog with the specified number of steps.</p>


```csharp
public ProgressDialog(string message, uint steps, bool delayedShow = false)
```
### ~ProgressDialog()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Progress dialog finalizer</p>


```csharp
protected ~ProgressDialog()
```
### Hide()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Hide the progress bar.</p>


```csharp
public void Hide()
```
### Show()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.ProgressDialog.yml" sourcestartlinenumber="1">Displays the progress dialog.</p>


```csharp
public void Show()
```


