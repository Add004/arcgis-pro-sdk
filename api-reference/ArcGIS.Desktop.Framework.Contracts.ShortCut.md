# ShortCut

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Represents a keyboard short-cut for a DAML command.</p>


## Object Signature

```csharp
public sealed class ShortCut
```


## Members

### CancelOnMouseMove

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets a boolean indicating whether this short-cut should be canceled if mouse moves.
This is only evaluated if ExecutesOnKeyUp is true.
The default value is false.</p>


```csharp
public bool CancelOnMouseMove { get; }
```
### CommandRefID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets the command ID associated with this short-cut.</p>


```csharp
public string CommandRefID { get; }
```
### DisplayString

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets the display string associated with this short-cut.</p>


```csharp
public string DisplayString { get; }
```
### ExecutesOnKeyUp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets a boolean indicating whether this short-cut should be executed on key up.
The default value is false.</p>


```csharp
public bool ExecutesOnKeyUp { get; }
```
### IsDisabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets a boolean indicating whether this shortcut is disabled.</p>


```csharp
public bool IsDisabled { get; set; }
```
### IsRemoved

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets a boolean indicating whether this shortcut is removed.</p>


```csharp
public bool IsRemoved { get; }
```
### Key

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets the key associated with this short-cut.</p>


```csharp
public Key Key { get; }
```
### Modifiers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ShortCut.yml" sourcestartlinenumber="1">Gets the modifier keys associated with this short-cut.</p>


```csharp
public ModifierKeys? Modifiers { get; }
```


