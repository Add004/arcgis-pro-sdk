# ReadOnlyDatastoreConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Core.Data.ReadOnlyDatastoreConfiguration.yml" sourcestartlinenumber="1">Represents a configuration of a datastore.
See <xref href="ArcGIS.Desktop.Core.EditingProjectExtender.GetSingleEditWorkspace(ArcGIS.Desktop.Core.Project)?text=GetSingleEditWorkspace" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.Core.EditingProjectExtender.GetSingleEditWorkspaceAsync(ArcGIS.Desktop.Core.Project)?text=GetSingleEditWorkspaceAsync" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ReadOnlyDatastoreConfiguration : IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.ReadOnlyDatastoreConfiguration.yml" sourcestartlinenumber="1">To ensure maximum robustness, callers should explicitly dispose of any <xref href="ArcGIS.Core.Data.ReadOnlyDatastoreConfiguration" data-throw-if-not-resolved="false"></xref> in either
a <code>using</code> statement or a <code>finally</code> block.</p>


## Members

### Datastore

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReadOnlyDatastoreConfiguration.yml" sourcestartlinenumber="1">Gets the datastore.</p>


```csharp
public Datastore Datastore { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.ReadOnlyDatastoreConfiguration.yml" sourcestartlinenumber="1">Releases this object's unmanaged resources.</p>


```csharp
public void Dispose()
```
### VersionState

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ReadOnlyDatastoreConfiguration.yml" sourcestartlinenumber="1">Gets the version state.</p>


```csharp
public VersionState VersionState { get; }
```


