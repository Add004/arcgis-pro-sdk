# AttachedProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.AttachedProperties.yml" sourcestartlinenumber="1">Attached properties used by the application framework.</p>


## Object Signature

```csharp
public static class AttachedProperties
```


## Members

### BlockShortcutsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.AttachedProperties.yml" sourcestartlinenumber="1">This attached property allows a control to block the application's keyboard shortcut processing.
For example, when a control has keyboard focus and an 'A' is entered, the application shortcut
framework will first check if a shortcut is registered to this key; if a shortcut is discovered, the
key event will get marked as handled and the control  might not receive the event. Note, several types of
controls are automatically removed from this framework including TextBox, EditBox, ListBox, and TreeView.
Use this attached property to add your control to this list.</p>


```csharp
public static readonly DependencyProperty BlockShortcutsProperty
```
### GetBlockShortcuts(DependencyObject)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.AttachedProperties.yml" sourcestartlinenumber="1">Gets the flag indicating if the applications keyboard shortcut processing is blocked for this control.</p>


```csharp
public static bool? GetBlockShortcuts(DependencyObject obj)
```
### SetBlockShortcuts(DependencyObject, bool?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.AttachedProperties.yml" sourcestartlinenumber="1">Sets the flag indicating if the applications keyboard shortcut processing is blocked for this control.</p>


```csharp
public static void SetBlockShortcuts(DependencyObject obj, bool? value)
```


