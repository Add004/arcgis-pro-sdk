# DockPaneState

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">DockPane positions.</p>


## Object Signature

```csharp
public enum DockPaneState
```


## Members

### AutoHide

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">Content is hosted by a fly-out window and is visible only when the user moves the mouse over an anchor thumb located in the application border.</p>


```csharp
AutoHide = 2
```
### DockableWindow

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">Content is hosted by a floating window and the user can re-dock it within the application.</p>


```csharp
DockableWindow = 3
```
### Docked

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">Content is docked within the application.</p>


```csharp
Docked = 1
```
### FloatingWindow

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">Content is hosted by a floating window that can't be docked within the application.</p>


```csharp
FloatingWindow = 4
```
### Hidden

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">Content is hidden.</p>


```csharp
Hidden = 5
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPaneState.yml" sourcestartlinenumber="1">Content is not associated with any <xref href="ArcGIS.Desktop.Framework.DockPaneManager" data-throw-if-not-resolved="false"></xref> (Default State).</p>


```csharp
None = 0
```


