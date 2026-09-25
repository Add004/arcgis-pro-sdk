# EditingProjectExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Core.EditingProjectExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend <xref href="ArcGIS.Desktop.Core.Project" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public static class EditingProjectExtender
```


## Members

### GetSingleEditWorkspace(Project)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingProjectExtender.yml" sourcestartlinenumber="1">Gets the current datastore being edited. This method will only return non-null values when
the project is configured for single workspace editing; that is <xref href="ArcGIS.Desktop.Core.EditingOptions.IsSingleWorkspaceEditSession" data-throw-if-not-resolved="false"></xref> is true.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReadOnlyDatastoreConfiguration GetSingleEditWorkspace(this Project project)
```
### GetSingleEditWorkspaceAsync(Project)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingProjectExtender.yml" sourcestartlinenumber="1">Gets the current datastore being edited. This method will only return non-null values when
the project is configured for single workspace editing; that is <xref href="ArcGIS.Desktop.Core.EditingOptions.IsSingleWorkspaceEditSession" data-throw-if-not-resolved="false"></xref> is true.</p>


```csharp
public static Task<ReadOnlyDatastoreConfiguration> GetSingleEditWorkspaceAsync(this Project project)
```
### SetSingleEditWorkspaceAsync(Project, Datastore)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingProjectExtender.yml" sourcestartlinenumber="1">Start a single edit workspace session using the specified datastore.</p>


```csharp
public static Task<bool> SetSingleEditWorkspaceAsync(this Project project, Datastore datastore)
```
### SetSingleEditWorkspaceAsync(Project, DatastoreConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingProjectExtender.yml" sourcestartlinenumber="1">Start a single edit workspace session using the specified datastore configuration.</p>


```csharp
public static Task<bool> SetSingleEditWorkspaceAsync(this Project project, DatastoreConfiguration datastoreConfig)
```
### SetSingleEditWorkspaceAsync(Project, MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingProjectExtender.yml" sourcestartlinenumber="1">Start a single edit workspace session using the datastore of the specified mapMember.</p>


```csharp
public static Task<bool> SetSingleEditWorkspaceAsync(this Project project, MapMember mapMember)
```


