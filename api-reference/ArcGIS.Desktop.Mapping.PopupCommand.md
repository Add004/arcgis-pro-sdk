# PopupCommand

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Represents a button shown at the bottom of the pop-up window.</p>


## Object Signature

```csharp
public sealed class PopupCommand : PropertyChangedBase
```


## Members

### PopupCommand(Action&lt;PopupContent&gt;, Func&lt;PopupContent, bool&gt;, string, ImageSource)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Initialize a new instance of a PopupCommand.</p>


```csharp
public PopupCommand(Action<PopupContent> execute, Func<PopupContent, bool> canExecute, string tooltip, ImageSource image)
```
### Command

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Internal command used for binding in the pop-up window.</p>


```csharp
public ICommand Command { get; }
```
### DisabledTooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Gets or sets the tooltip displayed when the command is disabled.</p>


```csharp
public string DisabledTooltip { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Internal id used to uniquely identify the command.</p>


```csharp
public string ID { get; }
```
### Image

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Gets or sets the image for the command.</p>


```csharp
public ImageSource Image { get; set; }
```
### IsSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Gets or sets a value that indicates if the command should place a separator between itself and the previous command.</p>


```csharp
public bool IsSeparator { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Internal name used by screen readers.</p>


```csharp
public string Name { get; }
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupCommand.yml" sourcestartlinenumber="1">Gets or sets the tooltip for the command.</p>


```csharp
public string Tooltip { get; set; }
```


