# EditingFrameworkExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Core.EditingFrameworkExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend ArcGIS.Desktop.Framework members.</p>


## Object Signature

```csharp
public static class EditingFrameworkExtender
```


## Members

### CanOpenExternalTablePane(PaneCollection, Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingFrameworkExtender.yml" sourcestartlinenumber="1">Determines if the item can be opened by the table pane.</p>


```csharp
public static bool CanOpenExternalTablePane(this PaneCollection paneCollection, Item item)
```
### GetExternalTableView(PaneCollection, Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingFrameworkExtender.yml" sourcestartlinenumber="1">Gets or creates the CIMExternalTableView for an item. If the table pane has been opened for this item, it will initialize the CIMExternalTableView with the previous values.
If table pane has never been opened, it will initialize the CIMExternalTableView with the default table pane values.</p>


```csharp
public static CIMExternalTableView GetExternalTableView(this PaneCollection paneCollection, Item item)
```
### OpenExternalTablePane(PaneCollection, CIMExternalTableView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingFrameworkExtender.yml" sourcestartlinenumber="1">Open a table pane for an Item. If a table pane is already open it will be activated.
You must be on the UI thread to call this function.</p>


```csharp
public static IExternalTablePane OpenExternalTablePane(this PaneCollection paneCollection, CIMExternalTableView externalTableView)
```
### OpenExternalTablePane(PaneCollection, Item, TableViewMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EditingFrameworkExtender.yml" sourcestartlinenumber="1">Open an external table pane for an item. If a table pane is already open it will be activated.
You must be on the UI thread to call this function.</p>


```csharp
public static IExternalTablePane OpenExternalTablePane(this PaneCollection paneCollection, Item item, TableViewMode viewMode = 0)
```


