# CustomProjectItemBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Base class for deriving custom <i>project </i>items. Custom project items are
custom items that can be persisted within a project aprx.</p>


## Object Signature

```csharp
public abstract class CustomProjectItemBase : CustomItemBase, IMetadata, IProjectItem
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Custom project items require a custom project item <b><i>container</i></b>.
Refer to <xref href="ArcGIS.Desktop.Core.CustomProjectItemContainer%601" data-throw-if-not-resolved="false"></xref> for more details</p>


## Members

### CustomProjectItemBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public CustomProjectItemBase()
```
### CustomProjectItemBase(ItemInfoValue)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Constructor that takes an ItemInfoValue.</p>


```csharp
public CustomProjectItemBase(ItemInfoValue itemInfoValue)
```
### CustomProjectItemBase(string, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Overloaded constructor for use by 3rd parties. This constructor is never called
by the core Catalog.</p>


```csharp
public CustomProjectItemBase(string name, string catalogPath, string typeID, string containerType)
```
### GetInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Called when your custom project item is being <b>added</b> to the project.</p>


```csharp
public ProjectItemInfo GetInfo()
```
### IncludeInPackages(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Use to include the custom item within packages and project templates</p>


```csharp
public void IncludeInPackages(bool includeInPackages)
```
### OnAddToProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Callback when your custom item is being added to the project</p>


```csharp
public virtual void OnAddToProject()
```
### OnGetInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Returns a ProjectItemInfo needed to add your custom project item information
to a given project.</p>


```csharp
public abstract ProjectItemInfo OnGetInfo()
```
### OnRemoveFromProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemBase.yml" sourcestartlinenumber="1">Callback when your custom item is being removed from the project</p>


```csharp
public virtual void OnRemoveFromProject()
```


