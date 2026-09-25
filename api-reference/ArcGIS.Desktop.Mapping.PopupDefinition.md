# PopupDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupDefinition.yml" sourcestartlinenumber="1">Describes a popup definition.</p>


## Object Signature

```csharp
public class PopupDefinition
```


## Members

### PopupDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupDefinition.yml" sourcestartlinenumber="1">Initialize a new instance of a PopupDefinition.</p>


```csharp
public PopupDefinition()
```
### Append

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupDefinition.yml" sourcestartlinenumber="1">Gets or sets whether content already in the dockable window is kept or cleared.
Only used when dockable is true.</p>


```csharp
public bool Append { get; set; }
```
### Dockable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupDefinition.yml" sourcestartlinenumber="1">Gets or sets whether the popup content is added to the default dockable window or a new pinned window.</p>


```csharp
public bool Dockable { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupDefinition.yml" sourcestartlinenumber="1">Gets or sets the screen coordinates to place the top left corner of the popup window. When set to null, a default position will be used.
Only used when dockable is false or the dockable window is floating.</p>


```csharp
public Point? Position { get; set; }
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupDefinition.yml" sourcestartlinenumber="1">Gets or sets the size of the popup window. When set to null, a default size will be used.
Only used when dockable is false or the dockable window is floating.</p>


```csharp
public Size? Size { get; set; }
```


