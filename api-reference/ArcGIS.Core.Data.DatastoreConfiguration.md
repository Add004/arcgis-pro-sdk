# DatastoreConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Core.Data.DatastoreConfiguration.yml" sourcestartlinenumber="1">Represents a configuration of a datastore.
See <xref href="ArcGIS.Desktop.Core.EditingProjectExtender.SetSingleEditWorkspaceAsync(ArcGIS.Desktop.Core.Project%2cArcGIS.Core.Data.DatastoreConfiguration)?text=SetSingleEditWorkspaceAsync" data-throw-if-not-resolved="false"></xref> for editing an
enterprise geodatabase when it has a mixture of versioned and non-versioned datasets.</p>


## Object Signature

```csharp
public sealed class DatastoreConfiguration
```


## Members

### DatastoreConfiguration(Datastore, VersionState)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DatastoreConfiguration.yml" sourcestartlinenumber="1">Initializes an instance of <xref href="ArcGIS.Core.Data.DatastoreConfiguration" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DatastoreConfiguration(Datastore datastore, VersionState versionState)
```
### Datastore

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatastoreConfiguration.yml" sourcestartlinenumber="1">Gets and sets the datastore.</p>


```csharp
public Datastore Datastore { get; set; }
```
### VersionState

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatastoreConfiguration.yml" sourcestartlinenumber="1">Gets and sets the version state.  The default value is <xref href="ArcGIS.Core.Data.VersionState.Versioned" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public VersionState VersionState { get; set; }
```


