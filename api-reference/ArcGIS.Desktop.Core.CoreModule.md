# CoreModule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Represents the core module, which provides access to the current project</p>


## Object Signature

```csharp
public sealed class CoreModule : Module, IPersistModule, ICoreModuleFileHandler
```


## Members

### CurrentProject

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Gets the project that is currently open in the ArcGIS Pro application</p>


```csharp
public static Project CurrentProject { get; set; }
```
### GetSuggestedCMDIDs(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Gets the suggested daml ids for the given tab identified by
'activeTabID'</p>


```csharp
public override string[] GetSuggestedCMDIDs(string activeTabID)
```
### OneDriveFileStatusDockPaneId

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Represents the core module, which provides access to the current project</p>


```csharp
public const string OneDriveFileStatusDockPaneId = "esri_core_oneDriveFileStatusDockPane"
```
### RepathProjectItem(ItemInfoValue, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Repath the item's catalog path to the path provided</p>


```csharp
public bool RepathProjectItem(ItemInfoValue projectItem, string newPath)
```
### RepathProjectItemAsync(ItemInfoValue, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Repath the item's catalog path to the path provided asynchronously</p>


```csharp
public Task<bool> RepathProjectItemAsync(ItemInfoValue projectItem, string newPath)
```
### ShowAdvancedItemPopups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Controls whether pop-ups appear in the Catalog pane and views with or without details.</p>


```csharp
public bool ShowAdvancedItemPopups { get; set; }
```
### ShowItemPopups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CoreModule.yml" sourcestartlinenumber="1">Controls whether pop-ups appear in the Catalog pane and views.</p>


```csharp
public bool ShowItemPopups { get; set; }
```


