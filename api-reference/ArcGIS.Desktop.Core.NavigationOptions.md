# NavigationOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.NavigationOptions.yml" sourcestartlinenumber="1">Gets and sets the application navigation options.</p>


## Object Signature

```csharp
public class NavigationOptions
```


## Members

### AutoPilotSpeed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.NavigationOptions.yml" sourcestartlinenumber="1">Gets and sets the amount of time in seconds the application takes to move from
one visible extent to another.</p>


```csharp
public double AutoPilotSpeed { get; set; }
```
### DefaultNavigationControlScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.NavigationOptions.yml" sourcestartlinenumber="1">Gets and sets an adjustment to the initial size of the navigator control
as it appears each time in a new view.</p>


```csharp
public double DefaultNavigationControlScale { get; set; }
```
### OnScreen2DNavigatorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.NavigationOptions.yml" sourcestartlinenumber="1">Gets and sets the 2D navigation mode for the
Navigator control whenever a new map is opened.</p>


```csharp
public NavigatorMode OnScreen2DNavigatorMode { get; set; }
```
### OnScreen3DNavigatorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.NavigationOptions.yml" sourcestartlinenumber="1">Gets and sets the 3D navigation mode for the
Navigator control whenever a new scene is opened.</p>


```csharp
public NavigatorMode OnScreen3DNavigatorMode { get; set; }
```


