# Project

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Represents an ArcGIS Pro project</p>


## Object Signature

```csharp
public sealed class Project : PropertyChangedBase, IMetadata
```

## Remarks

<p>
    An ArcGIS Pro project must be created or opened before you can start to use the application
    </p>


## Members

### AccessConstraints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets documented limitations with respect to using the item.
Derived from Use Limitations defined in the item's metadata.</p>


```csharp
public string AccessConstraints { get; }
```
### AddItem(IProjectItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Adds the item to the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool AddItem(IProjectItem item)
```
### CanEdit()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Indicates if metadata is editable for the item.</p>


```csharp
public bool CanEdit()
```
### CanOpen(string, out string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Checks if the specified project or project package can be opened</p>


```csharp
public static bool CanOpen(string projectOrPackageUri, out string docVersion)
```
### ClearPinnedProjectTemplates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Clears the list of recent project templates.</p>


```csharp
public static void ClearPinnedProjectTemplates()
```
### ClearPinnedProjects()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Clears the list of pinned projects.</p>


```csharp
public static void ClearPinnedProjects()
```
### ClearRecentProjectTemplates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Clears the list of recent project templates.</p>


```csharp
public static void ClearRecentProjectTemplates()
```
### ClearRecentProjects()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Clears the list of recent projects.</p>


```csharp
public static void ClearRecentProjects()
```
### CopyMetadataFromItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Copy metadata from Item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CopyMetadataFromItem(Item sourceItem)
```
### CreateAsync(CreatePortalProjectSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Creates a new portal project using the specified portal project settings.</p>


```csharp
public static Task<Project> CreateAsync(CreatePortalProjectSettings createPortalProjectSettings)
```
### CreateAsync(CreateProjectSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Creates a new project with properties determined by CreateProjectSettings</p>


```csharp
public static Task<Project> CreateAsync(CreateProjectSettings createProjectSettings = null)
```
### Credits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets information that gives credit to the producer or provider of the item.
Derived from Credits defined in the item's metadata.</p>


```csharp
public string Credits { get; }
```
### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the project that is currently open in the ArcGIS Pro application</p>


```csharp
public static Project Current { get; }
```
### DefaultGeodatabasePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the current project's default geodatabase</p>


```csharp
public string DefaultGeodatabasePath { get; }
```
### DefaultToolboxPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the current project's default toolbox</p>


```csharp
public string DefaultToolboxPath { get; }
```
### DeleteMetadataContent(MDDeleteContentOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Delete certain content from  the metadata of the current item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteMetadataContent(MDDeleteContentOption deleteOption)
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a description of the item.
Derived from the Description or Abstract defined in the item's metadata.</p>


```csharp
public string Description { get; }
```
### DiscardEditsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Discards all unsaved data edits in the project.</p>


```csharp
public Task<bool> DiscardEditsAsync()
```
### EditedDatastores

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Returns the data stores that have pending edits which have not been saved. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Datastore> EditedDatastores { get; }
```
### ExportMetadata(string, MDImportExportOption, MDExportRemovalOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Export metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportMetadata(string outputFilePath, MDImportExportOption exportType, MDExportRemovalOption removalOption)
```
### ExportMetadata(string, MDImportExportOption, MDExportRemovalOption, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Export metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportMetadata(string outputFilePath, MDImportExportOption exportType, MDExportRemovalOption removalOption, string styleSheetPath)
```
### FindItem(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Find the item identified by the physical path.</p>


```csharp
public Item FindItem(string path)
```
### GetActiveCatalogWindow()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the active catalog view or null if no catalog view is active</p>


```csharp
public static IProjectWindow GetActiveCatalogWindow()
```
### GetCatalogPane(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the catalog dockpane. If <b>createIfNecessary</b> = true and the catalog dockpane has not been
created, the pane will be created. Otherwise, if the catalog dockpane has not been created and
<b>createIfNecessary</b> = false, null will be returned.</p>


```csharp
public static IProjectWindow GetCatalogPane(bool createIfNecessary = true)
```
### GetDefaultProjectSettings()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Get the default project settings</p>


```csharp
public static CreateProjectSettings GetDefaultProjectSettings()
```
### GetItems&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a collection of a specific type of items within the project</p>


```csharp
public IEnumerable<T> GetItems<T>() where T : Item
```
### GetPinnedProjectTemplates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Retrieves the list of pinned project templates.</p>


```csharp
public static IReadOnlyList<string> GetPinnedProjectTemplates()
```
### GetPinnedProjects()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Retrieves the list of pinned projects.</p>


```csharp
public static IReadOnlyList<string> GetPinnedProjects()
```
### GetProjectItemContainer(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Get the container with the given key. Container keys are not localized. A container is needed
only in those situations where you want to select a specific item that occurs in
more than one container.</p>


```csharp
public Item GetProjectItemContainer(string key)
```
### GetRecentProjectTemplates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Retrieves the list of recently opened project templates</p>


```csharp
public static IReadOnlyList<string> GetRecentProjectTemplates()
```
### GetRecentProjects()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Retrieves the list of recently opened projects</p>


```csharp
public static IReadOnlyList<string> GetRecentProjects()
```
### GetRecentProjectsEx()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Retrieves the list of recently opened projects</p>


```csharp
public static IReadOnlyList<Tuple<string, string>> GetRecentProjectsEx()
```
### GetXml()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the items metadata XML document as a string.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetXml()
```
### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a unique identifier for the item</p>


```csharp
public string Guid { get; }
```
### HasEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets if there are any unsaved data edits in the project.</p>


```csharp
public bool HasEdits { get; }
```
### HomeFolderPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the current project's home folder</p>


```csharp
public string HomeFolderPath { get; }
```
### ImportItem(IProjectMultiItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Imports an item to the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IEnumerable<IProjectItem> ImportItem(IProjectMultiItem item)
```
### ImportItem(IProjectMultiItem, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Imports an item to the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IEnumerable<IProjectItem> ImportItem(IProjectMultiItem item, bool openPaneAfterImport, bool useExistingMaps = false)
```
### ImportMetadata(string, MDImportExportOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Import metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ImportMetadata(string catalogPathOrMDUri, MDImportExportOption importType)
```
### ImportMetadata(string, MDImportExportOption, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Import metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ImportMetadata(string catalogPathOrMDUri, MDImportExportOption importType, string styleSheetPath)
```
### IsDirty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the dirty state of the project</p>


```csharp
public bool IsDirty { get; }
```
### IsEditingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a value that indicates if editing is enabled.</p>


```csharp
public bool IsEditingEnabled { get; }
```
### IsPortalProject

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">If true, this project is a portal project.</p>


```csharp
public bool IsPortalProject { get; }
```
### IsPortalProjectDownloading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets whether the portal project is downloading</p>


```csharp
public bool IsPortalProjectDownloading { get; }
```
### IsPortalProjectMergingLocal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets whether the portal project is being merged</p>


```csharp
public bool IsPortalProjectMergingLocal { get; set; }
```
### IsPortalProjectUploading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets whether the portal project is uploading</p>


```csharp
public bool IsPortalProjectUploading { get; }
```
### Items

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the current project's collection of project items</p>


```csharp
public ReadOnlyObservableCollection<Item> Items { get; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the maximum map scale at which the item should draw</p>


```csharp
public double MaxScale { get; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the minimum map scale at which the item should draw</p>


```csharp
public double MinScale { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the name of the project</p>


```csharp
public string Name { get; }
```
### OpenAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Opens an existing project or project package</p>


```csharp
public static Task<Project> OpenAsync(string projectUri)
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the project path</p>


```csharp
public string Path { get; }
```
### PhysicalPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the location where the item (i.e. project) is stored</p>


```csharp
public string PhysicalPath { get; }
```
### PinProject(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Pins a project.</p>


```csharp
public static void PinProject(string path)
```
### PinProjectTemplate(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Pins a project template.</p>


```csharp
public static void PinProjectTemplate(string path)
```
### ProjectItemContainers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the list of project item containers</p>


```csharp
public IEnumerable<Item> ProjectItemContainers { get; }
```
### PushChangesPortalProjectAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">If this project is a portal project, this method updates the project on the portal to match the local version. Local changes and new items will be pushed
to the portal. Differences on the portal will be overwritten. New items on the portal will be deleted.</p>


```csharp
public Task<bool> PushChangesPortalProjectAsync()
```
### ReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets if the project is opened in a read-only state</p>


```csharp
public bool ReadOnly { get; }
```
### RedoEditAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Restores the last data edit that was reversed in the project.</p>


```csharp
public Task<bool> RedoEditAsync()
```
### RefreshProjectItemsAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Refreshes the project item specified by <code class="paramref">path</code>.</p>


```csharp
public Task RefreshProjectItemsAsync(string path)
```
### RemoveItem(IProjectItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Removes the project item from the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool RemoveItem(IProjectItem item)
```
### RemoveItems(IEnumerable&lt;IProjectItem&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Removes project items from the current project. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool RemoveItems(IEnumerable<IProjectItem> items)
```
### RemoveRecentProject(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Removes the project entry corresponding to the given input path from the recent list of projects</p>


```csharp
public static void RemoveRecentProject(string path)
```
### RemoveRecentProjectTemplate(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Removes the project template entry corresponding to the given input path from
the recent list of project templates</p>


```csharp
public static void RemoveRecentProjectTemplate(string path)
```
### RepairProjectItems(string, string)

- Kind: method


```csharp
public void RepairProjectItems(string oldPath, string newPath)
```
### SaveAsAsync(CreatePortalProjectSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Saves a copy of the current project to a new portal item on the specified portal with the
specified name, then opens the new project</p>


```csharp
public Task<bool> SaveAsAsync(CreatePortalProjectSettings createPortalProjectSettings)
```
### SaveAsAsync(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Saves a copy of the current project file (*.aprx) to the specified location with the
specified file name, then opens the new project file</p>


```csharp
public Task<bool> SaveAsAsync(string savePath, bool overwrite = false)
```
### SaveAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Saves the project</p>


```csharp
public Task<bool> SaveAsync()
```
### SaveEditsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Save all unsaved data edits in the project.</p>


```csharp
public Task<bool> SaveEditsAsync()
```
### SaveFromUntitled(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Creates a new project from an untitled session</p>


```csharp
public Task<Project> SaveFromUntitled(string savePath, string projectName)
```
### SaveMetadataAsHTML(string, MDSaveAsHTMLOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Save the metadata of the current item as HTML. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveMetadataAsHTML(string outputFilePath, MDSaveAsHTMLOption outputType)
```
### SaveMetadataAsUsingCustomXSLT(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Save the metadata of the current item using customized XSLT. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveMetadataAsUsingCustomXSLT(string customXSLTFilePath, string outputFilePath)
```
### SaveMetadataAsXML(string, MDSaveAsXMLOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Save the metadata of the current item as XML. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveMetadataAsXML(string outputFilePath, MDSaveAsXMLOption outputType)
```
### SearchAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Searches the project for items that match the provided criteria</p>


```csharp
public Task<IEnumerable<Item>> SearchAsync(string query)
```
### SelectedItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the items that are currently selected in the Project pane or the Project view</p>


```csharp
public ReadOnlyObservableCollection<Item> SelectedItems { get; }
```
### SetDefaultGeoDatabasePath(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets the project's default geodatabase. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultGeoDatabasePath(string defaultGeoDatabase)
```
### SetDefaultToolboxPath(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets the current project's default toolbox. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultToolboxPath(string defaultToolbox)
```
### SetDirty(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets the dirty state of the project</p>


```csharp
public void SetDirty(bool dirty = true)
```
### SetHomeFolderPath(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets the current project's home folder. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetHomeFolderPath(string folderPath)
```
### SetHomeFolderPathAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets the current project's home folder. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task SetHomeFolderPathAsync(string folderPath)
```
### SetIsEditingEnabledAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets a value that indicates if editing is to be enabled or disabled within the application.</p>


```csharp
public Task<bool> SetIsEditingEnabledAsync(bool value)
```
### SetXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Sets the items metadata to the XML document provided as a string. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetXml(string xml)
```
### SourceModifiedTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the time when the item's source item was last modified</p>


```csharp
public TimeInstant SourceModifiedTime { get; set; }
```
### Summary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a summary describing the purpose of the item.
Derived from the Summary or Purpose defined in the item's metadata.</p>


```csharp
public string Summary { get; }
```
### Synchronize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Updates metadata with the current properties of the item. Metadata is created for the item if it doesn't already exist.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Synchronize()
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a comma-separated list of tags that describe the item.
Derived from Tags defined in the item's metadata.</p>


```csharp
public string Tags { get; }
```
### ThumbnailPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a path to a thumbnail that describes and helps to identify the item.
Derived from the Thumbnail that is extracted from the item's metadata.</p>


```csharp
public string ThumbnailPath { get; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a descriptive title for the item.
Derived from the Title in the item's metadata.</p>


```csharp
public string Title { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a localized string indicating the item's type, for example, shapefile</p>


```csharp
public string Type { get; }
```
### TypeKeywords

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets keywords associated with the item's type that support finding the item with a search</p>


```csharp
public string TypeKeywords { get; }
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the location of the current project; that is, the path to the current project file (*.aprx)</p>


```csharp
public string URI { get; }
```
### UndoEditAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Reverses the last data edit in the project.</p>


```csharp
public Task<bool> UndoEditAsync()
```
### UnpinProject(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Unpins a project.</p>


```csharp
public static void UnpinProject(string path)
```
### UnpinTemplateProject(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Unpins a project template.</p>


```csharp
public static void UnpinTemplateProject(string path)
```
### UntitledMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets if the project is opened in a read-only state</p>


```csharp
public bool UntitledMode { get; }
```
### UpgradeMetadata(MDUpgradeOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Upgrade the metadata of the current item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpgradeMetadata(MDUpgradeOption upgradeOption)
```
### Url

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets a URL that can be used to access the item</p>


```csharp
public string Url { get; }
```
### XMax

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the maximum value along the x-axis for the item's minimum bounding rectangle</p>


```csharp
public double XMax { get; }
```
### XMin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the minimum value along the x-axis for the item's minimum bounding rectangle</p>


```csharp
public double XMin { get; }
```
### YMax

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the maximum value along the y-axis for the item's minimum bounding rectangle</p>


```csharp
public double YMax { get; }
```
### YMin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Project.yml" sourcestartlinenumber="1">Gets the minimum value along the y-axis for the item's minimum bounding rectangle</p>


```csharp
public double YMin { get; }
```


