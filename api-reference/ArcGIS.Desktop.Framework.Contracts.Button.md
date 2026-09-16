# Button

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Button.yml" sourcestartlinenumber="1">Represents a button control. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Button : PlugIn, INotifyPropertyChanged
```

## Remarks

<p>
  All ribbon control elements share several attributes. The loadOnClick attribute determines when the control should be
  created by the framework. By default, controls appear enabled, but are not actually instantiated until they are
  clicked. This simple just-in-time (JIT) strategy improves resource utilization and startup time by deferring the instantiation
  of controls until they are initiated by the end user. Note that non-visible controls are never loaded until
  they become visible (or are executed programmatically), regardless of the value assigned to loadOnClick.
</p>
<p>
  Tooltips are defined using the tooltip sub-element and may span as many lines as necessary.  The image attribute is used
  to supply an image that will appear next to the tip text. Command tooltips also support a disabledText element, this string
  is additional displayed when the command is disabled.
</p>
<p>
  Most controls support multiple sizes in the ribbon. For example, a button can render small (small icon only),
  medium (small icon with text), and large (large icon over text). Use the smallImage and largeImage attributes to
  specify unique images for the different sizes.  Images don’t have to be graphics, you can also use XAML. You can
  also use overlayLargeImage and overlaySmallImage to draw a graphic or XAML overtop of the corresponding images. If
  the image should flip when running right-to-left, e.g. arrow buttons, set the flipImageRTL attribute to true.
</p>
<p>
  The disableIfBusy element is used to signal that the control should be disabled whenever the primary worker thread is
  busy. This prevents work from queuing up. This element is true by default. Controls that always need to be enabled such
  as the close application button should set this to false.
</p>
<p>
  All control declarations support a condition attribute allowing the assignment of a condition.  If the specified condition
  isn’t met, the control will be automatically disabled by the framework.  In addition, controls remain unloaded until their
  is met.  If no condition is specified, the control is assumed to be always relevant.
</p>


## Members

### Button()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Button.yml" sourcestartlinenumber="1">Represents a button control. This is an abstract class.</p>


```csharp
protected Button()
```
### IsChecked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Button.yml" sourcestartlinenumber="1">Gets or sets whether the <xref href="ArcGIS.Desktop.Framework.Contracts.Button" data-throw-if-not-resolved="false"></xref> is checked.</p>


```csharp
public bool IsChecked { get; set; }
```
### OnClick()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Button.yml" sourcestartlinenumber="1">Called when the Button is clicked.</p>


```csharp
protected virtual void OnClick()
```


