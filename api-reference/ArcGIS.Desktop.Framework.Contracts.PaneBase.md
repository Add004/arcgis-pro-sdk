# PaneBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Represents the base class for Panes and DockPanes. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class PaneBase : PlugIn, INotifyPropertyChanged, IDropTarget
```


## Members

### CanCopyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's Copy button.</p>


```csharp
protected virtual Task<bool> CanCopyAsync()
```
### CanCopyPathAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's CopyPath button.</p>


```csharp
protected virtual Task<bool> CanCopyPathAsync()
```
### CanCutAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's Cut button.</p>


```csharp
protected virtual Task<bool> CanCutAsync()
```
### CanDeleteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's Delete button.</p>


```csharp
protected virtual Task<bool> CanDeleteAsync()
```
### CanDuplicateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's Duplicate button.</p>


```csharp
protected virtual Task<bool> CanDuplicateAsync()
```
### CanPasteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's Paste button.</p>


```csharp
protected virtual Task<bool> CanPasteAsync()
```
### CanPasteSpecialAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">The active pane is constantly polled giving it the opportunity to enable the application's PasteSpecial button.</p>


```csharp
protected virtual Task<bool> CanPasteSpecialAsync()
```
### CopyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the Copy command is clicked.</p>


```csharp
protected virtual Task CopyAsync()
```
### CopyPathAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the CopyPath command is clicked.</p>


```csharp
protected virtual Task<string> CopyPathAsync()
```
### CutAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the Cut command is executed.</p>


```csharp
protected virtual Task CutAsync()
```
### DeleteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the Delete command is executed.</p>


```csharp
protected virtual Task DeleteAsync()
```
### DuplicateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the Duplicate command is executed.</p>


```csharp
protected virtual Task DuplicateAsync()
```
### InitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the pane is first created to give it the opportunity to initialize itself asynchronously.</p>


```csharp
protected virtual Task InitializeAsync()
```
### Initialized

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Gets a boolean indicating whether the pane has been fully initialized or not.</p>


```csharp
public bool Initialized { get; }
```
### OnDragOver(DropInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Invoked when an object is dragged over the window. Implement this method to add class
handling for this event.</p>


```csharp
public virtual void OnDragOver(DropInfo dropInfo)
```
### OnDrop(DropInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Invoked when an object is dropped onto the pane. Implement this method to add class
handling for this event.</p>


```csharp
public virtual void OnDrop(DropInfo dropInfo)
```
### OnKeyCommand(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called during OnKeyDown if when a register shortcut matches.</p>


```csharp
protected virtual void OnKeyCommand(string commandID)
```
### OnMouseHWheel(short, short, short, short)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Invoked when an object is dragged over the window. Implement this method to add class
handling for this event.</p>


```csharp
public virtual void OnMouseHWheel(short xPos, short yPos, short keyState, short wheelDelta)
```
### PasteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the Paste command is executed.</p>


```csharp
protected virtual Task PasteAsync()
```
### PasteSpecialAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the PasteSpecial command is executed.</p>


```csharp
protected virtual Task PasteSpecialAsync()
```
### UninitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PaneBase.yml" sourcestartlinenumber="1">Called when the pane is closed to give it the opportunity to uninitialize itself asynchronously.</p>


```csharp
protected virtual Task UninitializeAsync()
```


