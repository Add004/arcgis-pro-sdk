# ProScreenTip

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Represents a screen tip that is a drop-in replacement for <xref href="System.Windows.Controls.ToolTip" data-throw-if-not-resolved="false"></xref>, but designed to show rich content with a specific appearance.</p>


## Object Signature

```csharp
public class ProScreenTip : ScreenTip, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild
```


## Members

### ProScreenTip()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public ProScreenTip()
```
### CmdWrapper

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Gets and sets the CmdWrapper</p>


```csharp
public IPlugInWrapper CmdWrapper { get; set; }
```
### DisabledText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Gets and sets the DisabledText</p>


```csharp
public string DisabledText { get; set; }
```
### DisabledTextProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Gets the DisabledTextProperty</p>


```csharp
public static readonly DependencyProperty DisabledTextProperty
```
### HelpUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Gets and sets the HelpUri</p>


```csharp
public Uri HelpUri { get; set; }
```
### HelpUriProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Gets the HelpUriProperty</p>


```csharp
public static readonly DependencyProperty HelpUriProperty
```
### ImageSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">Gets and sets the ImageSource</p>


```csharp
public ImageSource ImageSource { get; set; }
```
### OnOpened(RoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.ProScreenTip.yml" sourcestartlinenumber="1">OnOpened event handler</p>


```csharp
protected override void OnOpened(RoutedEventArgs e)
```


