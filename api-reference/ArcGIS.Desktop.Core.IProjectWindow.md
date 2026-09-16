# IProjectWindow

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Use this interface to select items and retrieve the current selection</p>


## Object Signature

```csharp
public interface IProjectWindow
```


## Members

### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Clear the current selection</p>


```csharp
void ClearSelection()
```
### RemoveAliasSelectedItem()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Removed the alias for the selected item.</p>


```csharp
Task<bool> RemoveAliasSelectedItem()
```
### RenameAliasSelectedItem()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Puts the selected item in rename mode for the alias in the user interface.</p>


```csharp
void RenameAliasSelectedItem()
```
### RenameItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Rename the item</p>


```csharp
void RenameItem(Item item)
```
### RenameSelectedItem()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Puts the selected Item in rename mode in the user interface</p>


```csharp
void RenameSelectedItem()
```
### SelectItemAsync(Item, bool, bool, Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Select an Item</p>


```csharp
Task SelectItemAsync(Item Item, bool select, bool expand, Item container)
```
### SelectedItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">Gets the currently selected Items</p>


```csharp
IEnumerable<Item> SelectedItems { get; }
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectWindow.yml" sourcestartlinenumber="1">The number of selected Items</p>


```csharp
int SelectionCount { get; }
```


