# VersioningOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.VersioningOptions.yml" sourcestartlinenumber="1">Gets and sets the application versioning options.</p>


## Object Signature

```csharp
public class VersioningOptions
```


## Members

### ConflictResolution

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VersioningOptions.yml" sourcestartlinenumber="1">Gets and sets the value defining how conflicts are resolved.</p>


```csharp
public ConflictResolutionType ConflictResolution { get; set; }
```
### DefineConflicts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VersioningOptions.yml" sourcestartlinenumber="1">Gets and sets the value defining how conflicts are flagged.</p>


```csharp
public ConflictDetectionType DefineConflicts { get; set; }
```
### IsTraditional

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VersioningOptions.yml" sourcestartlinenumber="1">Gets and sets the value indicating if new geodatabase connections default to traditional versioned.</p>


```csharp
public bool IsTraditional { get; set; }
```
### ShowConflictsDialog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VersioningOptions.yml" sourcestartlinenumber="1">Gets and sets the value indicating if a dialog is displayed to review conflicts.</p>


```csharp
public bool ShowConflictsDialog { get; set; }
```
### ShowReconcileDialog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VersioningOptions.yml" sourcestartlinenumber="1">Gets and sets the value indicating if a dialog is displayed during the reconcile process.</p>


```csharp
public bool ShowReconcileDialog { get; set; }
```


