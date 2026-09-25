# DockPane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Represents the base class for DockPanes. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class DockPane : PaneBase, INotifyPropertyChanged, IDropTarget, IFrameworkWindow
```

## Remarks

<p>
     Dock panes are modeless dialogs that can be docked at the top, right, left, or bottom of the view area within 
     the application.  Dock panes can also be: grouped with other dock panes, docked relative to each other (i.e. 
     below, above, etc), or floated.  Finally, dock panes can also be pinned/un-pinned so 
     that they slide back into the frame to save space. The framework persists and preserves the docking state of each dock pane
     so that when they are shown in subsequent sessions, they appear in their last position.
     </p>
<p>
     Dock panes are singletons: there is never more than one instance of a particular dock pane and once created, 
     they are not destroyed until the application shuts down. Use <xref href="ArcGIS.Desktop.Framework.DockPaneManager.Find(System.String)" data-throw-if-not-resolved="false"></xref> to access a specific dock pane. 
     </p>
<p>
     Declaring DockPanes in DAML:
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="15"> &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;&lt;dockPanes&gt;
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="16">&lt;dockPane id=&quot;acme_TOCDockPane&quot; caption=&quot;Contents&quot; className=&quot;TOCViewModel&quot;
condition=&quot;acme_basicPane&quot; dock=&quot;group&quot; dockWith=&quot;acme_ProjectDockPane&quot;&gt;
&lt;content className=&quot;TOC.TOCDockPane&quot;/&gt;
&lt;/dockPane&gt;
&lt;/dockPanes&gt;</p>
<p>
<table><thead><tr><th class="term">DAML attributes</th></tr></thead><tbody><tr><td class="term">id</td><td class="description">Required identifier.</td></tr><tr><td class="term">caption</td><td class="description">The default DockPane heading.</td></tr><tr><td class="term">extendedCaption</td><td class="description">A more descriptive title.</td></tr><tr><td class="term">isDropTarget</td><td class="description">Flag specifying whether the DockPane processes drag and drop events directly. Defaults to false.</td></tr><tr><td class="term">smallImage</td><td class="description">Image appearing in tab header.</td></tr><tr><td class="term">autoHide</td><td class="description">Flag specifying whether the DockPane comes up pinned or unpinned. Default is false, unpinned.</td></tr><tr><td class="term">delayLoadMessage</td><td class="description">Message that appears when DockPane is created from persisted dock state but it is currently out of context.</td></tr><tr><td class="term">dock</td><td class="description">Where the DockPane should initially appear.</td></tr><tr><td class="term">dockWith</td><td class="description">The DAML ID of the DockPane to dock relative to.</td></tr><tr><td class="term">hasHelp</td><td class="description">Show the help button.</td></tr><tr><td class="term">height</td><td class="description">The initial height. Used when applicable.</td></tr><tr><td class="term">helpContextID</td><td class="description">For Esri internal use.</td></tr><tr><td class="term">image</td><td class="description">Image for DockPane.</td></tr><tr><td class="term">width</td><td class="description">The initial width. Used when applicable.</td></tr><tr><td class="term">className</td><td class="description">Required class identifier. Optionally include namespace if not in default namespace.</td></tr><tr><td class="term">assembly</td><td class="description">Assembly name if not in the default assembly.</td></tr><tr><td class="term">publicKeyToken</td><td class="description">The necessary public key token if the assembly is strongly named.</td></tr><tr><td class="term">version</td><td class="description">The version of the dll if the assembly is strongly named.</td></tr></tbody></table>



## Members

### Activate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Activates the DockPane and gives it focus.</p>


```csharp
public void Activate()
```
### Activate(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Activates the DockPane.</p>


```csharp
public void Activate(bool focus)
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets or sets the DockPane's caption.</p>


```csharp
public string Caption { get; set; }
```
### Content

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets or sets the content portion of the DockPane.</p>


```csharp
protected FrameworkElement Content { get; set; }
```
### DockState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets the DockPane's position.</p>


```csharp
public DockPaneState DockState { get; }
```
### HelpContextID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets or sets the help topic ID to show.</p>


```csharp
protected string HelpContextID { get; set; }
```
### Hide()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Hides the DockPane.</p>


```csharp
public void Hide()
```
### IsBusy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets a boolean to let clients know the DockPane is currently processing a Task.</p>


```csharp
public virtual bool IsBusy { get; }
```
### IsFloating

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets the DockPane's floating state.</p>


```csharp
public bool IsFloating { get; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets or sets the DockPane's visibility.</p>


```csharp
public bool IsVisible { get; set; }
```
### OnActivate(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Called whenever the DockPane is activated or deactivated.</p>


```csharp
protected virtual void OnActivate(bool isActive)
```
### OnCreateContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Optional override to create the visible content of the control.</p>


```csharp
protected virtual Control OnCreateContent()
```
### OnHelpRequested()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Help requested for the DockPane.</p>


```csharp
protected virtual void OnHelpRequested()
```
### OnHidden()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Called when the DockPane is completely hidden.</p>


```csharp
protected virtual void OnHidden()
```
### OnSetContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Called when the <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane.Content" data-throw-if-not-resolved="false"></xref> is specified.</p>


```csharp
protected virtual void OnSetContent()
```
### OnShow(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Called when the visibility of the DockPane changes.</p>


```csharp
protected virtual void OnShow(bool isVisible)
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets the OperationManager associated with the DockPane.</p>


```csharp
public virtual OperationManager OperationManager { get; }
```
### Pin()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Pins the DockPane</p>


```csharp
public void Pin()
```
### ProcessKeyDown(KeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Process key down</p>


```csharp
protected void ProcessKeyDown(KeyEventArgs e)
```
### TabText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Gets or sets the dockpane's lower tab text. This appears only when the dock pane is grouped with other tabs.</p>


```csharp
public string TabText { get; set; }
```
### UnPin()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DockPane.yml" sourcestartlinenumber="1">Restores the DockPane from its pinned state.</p>


```csharp
public void UnPin()
```


