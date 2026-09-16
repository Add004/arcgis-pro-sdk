# IProjectView

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectView.yml" sourcestartlinenumber="1">Implemented on catalog view panes. Indicates whether the details view is being shown and the
parent item of any items that are selected.</p>


## Object Signature

```csharp
public interface IProjectView
```


## Members

### CurrentItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectView.yml" sourcestartlinenumber="1">Gets the current item. The current item will be the parent of any selected items in the
catalog view.</p>


```csharp
Item CurrentItem { get; }
```
### IsDetailsView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectView.yml" sourcestartlinenumber="1">Gets whether the details view is being shown</p>


```csharp
bool IsDetailsView { get; }
```


