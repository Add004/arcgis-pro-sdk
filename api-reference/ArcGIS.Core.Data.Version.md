# Version

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Represents a version in a given enterprise <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class Version : VersionBase, IDisposable
```


## Members

### Alter(VersionDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Changes this version's name, description and access permissions.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Alter(VersionDescription versionDescription)
```
### ChangeOwner(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Changes this version's owner.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ChangeOwner(string newOwnerName)
```
### Connect()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Physically connects to this version in the geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Geodatabase Connect()
```
### Delete()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Deletes this version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override void Delete()
```
### GetAccessType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets this version's access permission.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VersionAccessType GetAccessType()
```
### GetChildren()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets a list of all the available child versions.  If this version has no children, an empty list is returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Version> GetChildren()
```
### GetConflictSets()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets the mapping between container conflicts and the corresponding set of content conflicts.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<Guid, IReadOnlyList<Conflict>> GetConflictSets()
```
### GetConflicts()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets a list of all conflicts with the target version. If there are no conflicts, an empty list is returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Conflict> GetConflicts()
```
### GetCreatedDate()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets the date and time this version was created.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DateTime GetCreatedDate()
```
### GetDescription()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets this version's description.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDescription()
```
### GetModifiedDate()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets the date and time this version was last modified.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DateTime GetModifiedDate()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets the name of this version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override string GetName()
```
### GetParent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets this version's parent version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Version GetParent()
```
### HasConflicts()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets a value indicating whether conflicts exist in this version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasConflicts()
```
### IsOwner()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Gets a value indicating whether the current connected user is the owner of this version.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsOwner()
```
### Reconcile(ReconcileOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Reconciles this version against a target version specified in <code class="paramref">reconcileOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ReconcileResult Reconcile(ReconcileOptions reconcileOptions)
```
### Reconcile(ReconcileOptions, PartialPostOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Reconciles and partial posts this version against a target version specified in <code class="paramref">reconcileOptions</code> and <code class="paramref">partialPostOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ReconcileResult Reconcile(ReconcileOptions reconcileOptions, PartialPostOptions partialPostOptions)
```
### Reconcile(ReconcileOptions, PostOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Reconciles and posts this version against a target version specified in <code class="paramref">reconcileOptions</code> and <code class="paramref">postOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ReconcileResult Reconcile(ReconcileOptions reconcileOptions, PostOptions postOptions)
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Version.yml" sourcestartlinenumber="1">Refreshes the version with the corresponding database state.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Refresh()
```


