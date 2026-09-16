# GeneralOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the application general options.</p>


## Object Signature

```csharp
public class GeneralOptions
```


## Members

### CreateProjectBackups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets whether a backup is to be created when a project has unsaved changes. Use <xref href="ArcGIS.Desktop.Core.GeneralOptions.ProjectBackupInterval" data-throw-if-not-resolved="false"></xref> to define the time interval
for saving the backup.</p>


```csharp
public bool CreateProjectBackups { get; set; }
```
### CustomDefaultGeodatabase

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the path to the default geodatabase to use with new projects</p>


```csharp
public string CustomDefaultGeodatabase { get; set; }
```
### CustomDefaultToolbox

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the path to a toolbox to use as the default toolbox
for new projects</p>


```csharp
public string CustomDefaultToolbox { get; set; }
```
### CustomHomeFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the path to a custom default home folder location to use with
new projects</p>


```csharp
public string CustomHomeFolder { get; set; }
```
### DefaultGeodatabaseOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets whether new projects are created with a new file geodatabase
or with an existing geodatabase.</p>


```csharp
public OptionSetting DefaultGeodatabaseOption { get; set; }
```
### DefaultToolboxOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets whether new projects are created with a new toolbox
or with an existing toolbox.</p>


```csharp
public OptionSetting DefaultToolboxOption { get; set; }
```
### HomeFolderOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets whether new projects are saved to the default home folder
location or a custom location.</p>


```csharp
public OptionSetting HomeFolderOption { get; set; }
```
### MergingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets how the project is synced to server</p>


```csharp
public PortalProjectSyncType MergingStrategy { get; set; }
```
### PortalProjectCustomDefaultGeodatabase

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the default location for output files created in the local copy that
<b><i>are</i></b> saved to a geodatabase.</p>


```csharp
public string PortalProjectCustomDefaultGeodatabase { get; set; }
```
### PortalProjectCustomDefaultToolbox

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the default location for geoprocessing models created in
the local copy. A toolbox stored in a geodatabase cannot be the default
toolbox</p>


```csharp
public string PortalProjectCustomDefaultToolbox { get; set; }
```
### PortalProjectCustomHomeFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the default location for output files created in the local copy that
are <b><i>not</i></b> saved to a geodatabase.</p>


```csharp
public string PortalProjectCustomHomeFolder { get; set; }
```
### PortalProjectDeleteLocalCopyOnClose

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets whether the downloaded local copy of a portal project is
preserved when you close the project.</p>


```csharp
public bool PortalProjectDeleteLocalCopyOnClose { get; set; }
```
### PortalProjectDownloadLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the download location for portal projects</p>


```csharp
public string PortalProjectDownloadLocation { get; set; }
```
### PortalProjectUsageOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets how the project will be used</p>


```csharp
public PortalProjectUsageEnum PortalProjectUsageOption { get; set; }
```
### ProjectBackupInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the time interval (in minutes) to elapse after which a project backup is saved if <xref href="ArcGIS.Desktop.Core.GeneralOptions.CreateProjectBackups" data-throw-if-not-resolved="false"></xref> is true.</p>


```csharp
public int ProjectBackupInterval { get; set; }
```
### ProjectCreateInFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets whether to store the project file, project geodatabase,
and project toolbox in a folder named for the project.</p>


```csharp
public bool ProjectCreateInFolder { get; set; }
```
### StartupOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the application startup mode.</p>


```csharp
public StartProjectMode StartupOption { get; set; }
```
### StartupProjectPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeneralOptions.yml" sourcestartlinenumber="1">Gets and sets the path to a default project (.aprx) to use when the
application starts</p>


```csharp
public string StartupProjectPath { get; set; }
```


