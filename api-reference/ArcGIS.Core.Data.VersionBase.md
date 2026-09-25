# VersionBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.VersionBase.yml" sourcestartlinenumber="1">Represents either a version or a historical version in a <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class VersionBase : CoreObjectsBase, IDisposable
```


## Members

### VersionBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.VersionBase.yml" sourcestartlinenumber="1">Represents either a version or a historical version in a <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected VersionBase()
```
### Connect()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionBase.yml" sourcestartlinenumber="1">Connects to this VersionBase in the geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public abstract Geodatabase Connect()
```
### Delete()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionBase.yml" sourcestartlinenumber="1">Deletes this VersionBase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public abstract void Delete()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionBase.yml" sourcestartlinenumber="1">Gets the name of this VersionBase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public abstract string GetName()
```


