# DockPaneManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.DockPaneManager.yml" sourcestartlinenumber="1">This class manages the active <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane" data-throw-if-not-resolved="false"></xref> instances and supplies
the mechanism for instantiating new dock panes.</p>


## Object Signature

```csharp
public sealed class DockPaneManager
```


## Members

### DockPanes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DockPaneManager.yml" sourcestartlinenumber="1">Gets the instantiated dock panes.</p>


```csharp
public ReadOnlyObservableCollection<DockPane> DockPanes { get; }
```
### Find(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DockPaneManager.yml" sourcestartlinenumber="1">Returns the specified <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane" data-throw-if-not-resolved="false"></xref>. Instantiates the DockPane if necessary.</p>


```csharp
public DockPane Find(string id)
```
### HideAllDockPanes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DockPaneManager.yml" sourcestartlinenumber="1">Hides all the dock panes.</p>


```csharp
public void HideAllDockPanes()
```
### IsDockPaneCreated(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DockPaneManager.yml" sourcestartlinenumber="1">Checks if the specified <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane" data-throw-if-not-resolved="false"></xref> has been instantiated.</p>


```csharp
public bool IsDockPaneCreated(string id)
```
### IsVisible(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DockPaneManager.yml" sourcestartlinenumber="1">Checks if a dock pane is visible.</p>


```csharp
public bool IsVisible(string id)
```


