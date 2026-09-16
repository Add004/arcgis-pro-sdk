# CustomControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">Represents a user designed ribbon control. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class CustomControl : PlugIn, INotifyPropertyChanged
```

## Remarks

<p>
     Even though DAML supports a rich set of pre-defined ribbon controls, occasionally
     it may be necessary to author a custom control. The CustomControl class is the base class for
     these rare occasions.
     </p>
<p>
     There are two types of custom controls. The first type is a custom UIElement
     hosted directly in the ribbon control much like an in-line gallery. The second is a Framework drop down button
     that presents the custom control in a popup control. The later is very similar
     to a drop down gallery except in this case the control author has complete 
     control of the drop down.
     </p>
<p>
     For in-ribbon custom controls the control must be 22 pixels tall if the representation
     is small or middle, and 68 pixels if large.
     </p>


## Members

### CustomControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">Represents a user designed ribbon control. This is an abstract class.</p>


```csharp
protected CustomControl()
```
### ClosePopup()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">Close the Popup if hosted in a drop down button.</p>


```csharp
protected void ClosePopup()
```
### Content

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">Gets and sets the FrameworkElement associated with the PlugIn.</p>


```csharp
protected FrameworkElement Content { get; set; }
```
### Keytip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">Gets the key tip access text for the control.</p>


```csharp
protected string Keytip { get; }
```
### OnCreateContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">Called to create the PlugIn's visual component if not specified in DAML.</p>


```csharp
protected virtual FrameworkElement OnCreateContent()
```
### OnDropDownClosed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">If the CustomControl specifies the DAML attribute 'isDrop=true', this function is called whenever its drop-down is closed.</p>


```csharp
protected virtual void OnDropDownClosed()
```
### OnDropDownOpened()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomControl.yml" sourcestartlinenumber="1">If the CustomControl specifies the DAML attribute 'isDrop=true', this function is called whenever its drop-down is opened.</p>


```csharp
protected virtual void OnDropDownOpened()
```


