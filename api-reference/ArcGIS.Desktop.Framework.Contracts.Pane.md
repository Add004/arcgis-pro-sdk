# Pane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Represents a primary window within the application. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Pane : PaneBase, INotifyPropertyChanged, IDropTarget, IFrameworkWindow
```

## Remarks

<p>
     The framework supports multiple panes, letting users display and interact with multiple subjects.  Only 
     one pane can be active at a time.  The active pane helps establish what is available on the ribbon; switching 
     between different panes may result in changes to the visible tabs.  The active pane 
     represents what the user is working with at any given time and therefore provides the primary context for 
     the application. You can open many panes at the same time and these can be grouped or tiled.  
     </p>
<p>
     Panes can be associated with a default tab and a default tool such that if no other relevant tool/tab is 
     already selected, the default will automatically be selected when the pane is activated.
     </p>
<p>
     Panes have two components: a component class that derives from the Pane abstract class and 
     a view class that derives from FrameworkElement, typically a UserControl. Panes must be
     defined in DAML.
     </p>
<p>
     Declaring Panes in DAML:
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="20"> &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;&lt;panes&gt;
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="21">&lt;pane id=&quot;acme_basicPane&quot; className=&quot;BasicPaneViewModel&quot; caption=&quot;Basic Pane&quot; isDropTarget=&quot;true&quot; loadingMessage=&quot;Initializing...&quot;
defaultTab=&quot;acme_mainTab&quot; defaultTool=&quot;acme_selectTool&quot; smallImage=&quot;pack://application:,,,/Acme;component/Images/BasicPane.png&quot; &gt;
&lt;content className=&quot;BasicPaneView&quot;/&gt;
&lt;/pane&gt;
&lt;/panes&gt;</p>
<p>
<table><thead><tr><th class="term">DAML attributes</th></tr></thead><tbody><tr><td class="term">id</td><td class="description">Required identifier.</td></tr><tr><td class="term">caption</td><td class="description">The default Pane heading.</td></tr><tr><td class="term">extendedCaption</td><td class="description">A more descriptive title.</td></tr><tr><td class="term">loadingMessage</td><td class="description">Temporary message appearing while Pane is initializing.</td></tr><tr><td class="term">showLoadingMessage</td><td class="description">Loading message visibility.</td></tr><tr><td class="term">isDropTarget</td><td class="description">Flag specifying whether the Pane processes drag/drop events directly. Defaults to true.</td></tr><tr><td class="term">defaultTab</td><td class="description">Tab to activate when Pane activates.</td></tr><tr><td class="term">defaultTool</td><td class="description">Tool to activate when Pane activates.</td></tr><tr><td class="term">defaultDockPane</td><td class="description">DockPane to activate when Pane activates.</td></tr><tr><td class="term">hasCloseAllButThisCommand</td><td class="description">Enable or disable the 'Close all but this' command on the Pane's context menu.</td></tr><tr><td class="term">smallImage</td><td class="description">Image appearing in tab header.</td></tr><tr><td class="term">className</td><td class="description">Required class identifier. Optionally include namespace if not in default namespace.</td></tr><tr><td class="term">assembly</td><td class="description">Assembly name if not in the default assembly.</td></tr><tr><td class="term">publicKeyToken</td><td class="description">The necessary public key token if the assembly is strongly named.</td></tr><tr><td class="term">version</td><td class="description">The version of the dll if the assembly is strongly named.</td></tr></tbody></table>



## Members

### Activate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Makes the Pane the active Pane and active window.</p>


```csharp
public void Activate()
```
### CanClose

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets or sets whether the window may be closed.</p>


```csharp
public bool CanClose { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets or sets the Pane's caption.</p>


```csharp
public string Caption { get; set; }
```
### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Close the Pane.</p>


```csharp
public void Close()
```
### CombineState(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Combines the Pane's state with the specified Pane.</p>


```csharp
protected void CombineState(Pane pane)
```
### Content

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets or sets the content portion of the Pane.</p>


```csharp
protected FrameworkElement Content { get; set; }
```
### ContentID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Allows derived classes to provide a unique identifier for the Pane. The DAML ID is returned by default.</p>


```csharp
public virtual string ContentID { get; }
```
### Flash()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Flashes the Pane's tab.</p>


```csharp
public void Flash()
```
### FullCaption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets the Pane's Caption including its GroupID count.</p>


```csharp
public string FullCaption { get; }
```
### GroupID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Setting the GroupID property enables Pane numbering.</p>


```csharp
protected string GroupID { get; set; }
```
### GroupIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets the index assigned for the GroupID count.</p>


```csharp
public int GroupIndex { get; }
```
### Impersonate(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Allows a Pane to override the state it sets when activated.</p>


```csharp
protected void Impersonate(string paneID)
```
### InstanceID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets the Framework assigned ID.</p>


```csharp
public uint InstanceID { get; }
```
### IsBusy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets a boolean to let clients know the Pane is currently processing a Task.</p>


```csharp
public virtual bool IsBusy { get; }
```
### IsPermanantHidden

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">For internal esri use only</p>


```csharp
protected bool IsPermanantHidden { get; set; }
```
### LoadingMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets or sets the message presented while the Pane is initializing.</p>


```csharp
public string LoadingMessage { get; protected set; }
```
### OnActivate(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Called whenever the Pane is activated or deactivated.</p>


```csharp
protected virtual void OnActivate(bool isActive)
```
### OnClosed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Notification letting the Pane know it has been closed.</p>


```csharp
protected virtual void OnClosed()
```
### OnClosing(CancelRoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Called when a request has been made to close the Pane.</p>


```csharp
protected virtual void OnClosing(CancelRoutedEventArgs e)
```
### OnContextMenu(ContextMenu)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Provides the Pane with the option to customize its ContextMenu before it is displayed.</p>


```csharp
protected virtual void OnContextMenu(ContextMenu contextMenu)
```
### OnCreateContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Optional override to create the visible content of the control.</p>


```csharp
protected virtual FrameworkElement OnCreateContent()
```
### OnDocked()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Notification letting the Pane know it has been docked.</p>


```csharp
protected virtual void OnDocked()
```
### OnDoubleClick(MouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when a mouse button is clicked two or more times.</p>


```csharp
protected virtual void OnDoubleClick(MouseEventArgs e)
```
### OnFloated()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Notification letting the Pane know it has been floated.</p>


```csharp
protected virtual void OnFloated()
```
### OnHidden()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Notification letting the Pane know it has been hidden.</p>


```csharp
protected virtual void OnHidden()
```
### OnKeyDown(KeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when a key is pressed while focus is on this element.</p>


```csharp
protected virtual void OnKeyDown(KeyEventArgs k)
```
### OnKeyUp(KeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when a key is released while focus is on this element.</p>


```csharp
protected virtual void OnKeyUp(KeyEventArgs k)
```
### OnMouseDown(MouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when any mouse button is pressed while the pointer is over this element.</p>


```csharp
protected virtual void OnMouseDown(MouseButtonEventArgs e)
```
### OnMouseMove(MouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when the mouse pointer moves while over this element.</p>


```csharp
protected virtual void OnMouseMove(MouseEventArgs e)
```
### OnMouseUp(MouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when any mouse button is released over this element.</p>


```csharp
protected virtual void OnMouseUp(MouseButtonEventArgs e)
```
### OnPointerDown(RoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when a pointer is pressed while over this element.</p>


```csharp
protected virtual void OnPointerDown(RoutedEventArgs e)
```
### OnPointerUp(RoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when a pointer is released over this element.</p>


```csharp
protected virtual void OnPointerUp(RoutedEventArgs e)
```
### OnTouch(TouchInputEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Occurs when a touch event occurs over this element.</p>


```csharp
protected virtual void OnTouch(TouchInputEventArgs e)
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets the OperationManager associated with the Pane.</p>


```csharp
public virtual OperationManager OperationManager { get; }
```
### ProcessKeyDown(KeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Process key down</p>


```csharp
protected void ProcessKeyDown(KeyEventArgs e)
```
### Secondary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">This is for Esri internal use only.</p>


```csharp
public virtual bool Secondary { get; }
```
### State

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets the Pane's state table.</p>


```csharp
public State State { get; }
```
### TabTooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets or sets the Pane's tab tooltip.</p>


```csharp
public string TabTooltip { get; set; }
```
### ToolElement

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Gets or sets the Pane's HwndHost if applicable.</p>


```csharp
public FrameworkElement ToolElement { get; set; }
```
### Unimpersonate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Pane.yml" sourcestartlinenumber="1">Stops the Pane from impersonating a different state.</p>


```csharp
protected void Unimpersonate()
```


