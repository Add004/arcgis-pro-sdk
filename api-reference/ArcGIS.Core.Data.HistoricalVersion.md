# HistoricalVersion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.HistoricalVersion.yml" sourcestartlinenumber="1">Represents a historical version in a <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class HistoricalVersion : VersionBase, IDisposable
```


## Members

### Connect()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.HistoricalVersion.yml" sourcestartlinenumber="1">Connects to this historical version in the geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Geodatabase Connect()
```
### Delete()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.HistoricalVersion.yml" sourcestartlinenumber="1">Deletes this historical version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override void Delete()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.HistoricalVersion.yml" sourcestartlinenumber="1">Gets the name (i.e., marker) of this historical version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override string GetName()
```
### GetTimeStamp()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.HistoricalVersion.yml" sourcestartlinenumber="1">Get the date and time referenced by this historical version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DateTime GetTimeStamp()
```


