# Progressor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.html">Threading</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Threading.Tasks.html">Tasks</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Used by the executing Task to detect cancellation and update status information displayed the progress dialog during execution.</p>


## Object Signature

```csharp
public class Progressor
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets the current Progressor.</p>


```csharp
public static Progressor Current { get; }
```
### ExtendedStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets or sets the extended status displayed in the progress dialog.</p>


```csharp
public string ExtendedStatus { get; set; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets or sets the maximum range of the progress meter displayed in the progress dialog.</p>


```csharp
public uint Max { get; set; }
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets or sets message of the progress dialog.</p>


```csharp
public string Message { get; set; }
```
### None

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets an empty Progressor which does nothing.</p>


```csharp
public static Progressor None { get; }
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets or sets the status displayed in the progress dialog.</p>


```csharp
public string Status { get; set; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Threading.Tasks.Progressor.yml" sourcestartlinenumber="1">Gets or sets the position of the progress meter displayed in the progress dialog.</p>


```csharp
public uint Value { get; set; }
```


