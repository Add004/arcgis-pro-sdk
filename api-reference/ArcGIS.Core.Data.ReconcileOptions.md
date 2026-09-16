# ReconcileOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Represents a mechanism to reconcile a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ReconcileOptions
```


## Members

### ReconcileOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ReconcileOptions</code> class for a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to reconcile
with the <b>default</b> version.</p>


```csharp
public ReconcileOptions()
```
### ReconcileOptions(Version)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ReconcileOptions</code> class for a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to reconcile
with the <code class="paramref">targetVersion</code>.</p>


```csharp
public ReconcileOptions(Version targetVersion)
```
### ConflictDetectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Gets or sets the conflict detection type.</p>


```csharp
public ConflictDetectionType ConflictDetectionType { get; set; }
```
### ConflictResolutionMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Gets or sets the conflict resolution method.</p>


```csharp
public ConflictResolutionMethod ConflictResolutionMethod { get; set; }
```
### ConflictResolutionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Gets or sets the conflict resolution type.</p>


```csharp
public ConflictResolutionType ConflictResolutionType { get; set; }
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Gets or sets whether or not Reconcile should run synchronously.</p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```
### TargetVersion

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReconcileOptions.yml" sourcestartlinenumber="1">Gets the target <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to be reconciled against.  If <b>null</b>, the target is the <b>default</b> version.</p>


```csharp
public Version TargetVersion { get; }
```


