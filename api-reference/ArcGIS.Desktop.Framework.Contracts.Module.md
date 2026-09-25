# Module

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Represents the central access point for a sub-system. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Module : PropertyChangedBase, INotifyPropertyChanged
```

## Remarks

<p>
    Modules are singletons that are instantiated automatically by the Framework when access is explicitly requested in executing code, or 
    when the Module becomes "relevant" due to a context shift.  Modules have program elements that are explicitly declared as such; these elements 
    include: Ribbon Buttons, Tools, Galleries, Combo Boxes, Edit Boxes, Palettes, and other controls, as well as application Panes and Docking Panes.  
    The well-defined relationship between a Module and its associated components lets the application initialize, un-initialize, and remove entire 
    subsystems as a whole.
    </p>
<p>
    Modules act as the hub and central access point for their subsystem; if you need access to the functionality within a subsystem, you start with the Module. 
    By convention, all public properties and methods on Modules should be static; clients can reference the associated assembly and then directly use the Module 
    class without having to call Find (or pass the Module ID).
    </p>
<p>
    Most of the logic in a sub system should reside in a module or a helper (non-UI) class the module directly manages. For example, when writing a button, 
    the Button class itself should have no business logic in it; all the logic should be centralized in its parent module. Centralizing the business logic 
    reduces the spaghetti-effect. For example, instead of several buttons each listening to a particular event, it’s better to have one Module listen to the 
    event and each Button instead polls the Module in OnUpdate.
    </p>
<p>Modules support several patterns to make centralizing business logic much easier; for instance, modules automatically load whenever one 
    of their plug-ins (program elements) load.  For example, in most cases a button on the ribbon doesn’t load until it is clicked; when this happens, the button’s parent 
    Module is also loaded. Similarly, when a dock pane loads, its parent Module also loads.
    </p>
<p>Modules also have a pattern for working with Panes. Modules are automatically notified whenever one of its panes are activated, deactivated, 
    opened, or closed. This means a Module doesn’t have to listen to the Framework’s ActivePaneChanged event and from here filter for its panes; instead, 
    Modules are given direct notification that one of their panes changed.
    </p>
<p>
    Declaring Modules in DAML:
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="30">&lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;&lt;/code&gt;&lt;/pre&gt;&lt;/p&gt;
    &lt;p&gt;
        DAML attributes:
        &lt;/p&gt;
</code></pre>


## Members

### CanCopyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's Copy button.</p>


```csharp
protected virtual Task<bool> CanCopyAsync()
```
### CanCopyPathAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's Copy Path button.</p>


```csharp
protected virtual Task<bool> CanCopyPathAsync()
```
### CanCutAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's Cut button.</p>


```csharp
protected virtual Task<bool> CanCutAsync()
```
### CanDeleteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's Delete button.</p>


```csharp
protected virtual Task<bool> CanDeleteAsync()
```
### CanDuplicateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's Duplicate button.</p>


```csharp
protected virtual Task<bool> CanDuplicateAsync()
```
### CanPasteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's Paste button.</p>


```csharp
protected virtual Task<bool> CanPasteAsync()
```
### CanPasteSpecialAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Modules are constantly polled giving them the opportunity to enable the application's PasteSpecial button.</p>


```csharp
protected virtual Task<bool> CanPasteSpecialAsync()
```
### CanUnload()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">When overridden in a derived class, a Module can return that it can't be unloaded.</p>


```csharp
protected virtual bool CanUnload()
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Gets the name of the Module.</p>


```csharp
public string Caption { get; }
```
### CopyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the Copy command is executed.</p>


```csharp
protected virtual Task CopyAsync()
```
### CopyPathAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the CopyPath command is executed.</p>


```csharp
protected virtual Task<string> CopyPathAsync()
```
### CutAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the Cut command is executed.</p>


```csharp
protected virtual Task CutAsync()
```
### DeleteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the Delete command is executed.</p>


```csharp
protected virtual Task DeleteAsync()
```
### DuplicateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the Duplicate command is executed.</p>


```csharp
protected virtual Task DuplicateAsync()
```
### ExecuteCommand(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Override this method to allow users to execute DAML commands specified in this module.</p>


```csharp
protected virtual Func<Task> ExecuteCommand(string id)
```
### ExecuteCommandArgs(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Override this method to allow users to execute DAML commands specified in this module.</p>


```csharp
protected virtual Func<object[], Task> ExecuteCommandArgs(string id)
```
### GetSuggestedCMDIDs(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Gets the set of Search Suggestion IDs.</p>


```csharp
public virtual string[] GetSuggestedCMDIDs(string activeTabID)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Gets the DAML identifier.</p>


```csharp
protected string ID { get; }
```
### Initialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">When overridden in a derived class, gives the custom Module a chance to initialize itself and return its status to the calling Framework.</p>


```csharp
protected virtual bool Initialize()
```
### OnPaneActivated(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called by the Framework when a Pane is activated.</p>


```csharp
protected virtual void OnPaneActivated(Pane incomingPane)
```
### OnPaneClosed(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called by the Framework when a Pane is closed.</p>


```csharp
protected virtual void OnPaneClosed(Pane pane)
```
### OnPaneClosing(Pane, CancelRoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called by the Framework when one of the Module's Pane is about to close.</p>


```csharp
protected virtual void OnPaneClosing(Pane pane, CancelRoutedEventArgs e)
```
### OnPaneDeactivated(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called by the Framework when a Pane is deactivated.</p>


```csharp
protected virtual void OnPaneDeactivated(Pane outgoingPane)
```
### OnPaneOpened(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called by the Framework when a new Pane is opened. This occurs after the pane has been fully initialized.</p>


```csharp
protected virtual void OnPaneOpened(Pane pane)
```
### OnReadSettingsAsync(ModuleSettingsReader)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Override this method to read custom settings written to the current project.</p>


```csharp
protected virtual Task OnReadSettingsAsync(ModuleSettingsReader settings)
```
### OnUpdate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called periodically by the framework once the module has been loaded.</p>


```csharp
protected virtual void OnUpdate()
```
### OnWriteSettingsAsync(ModuleSettingsWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Override this method to write custom settings to the current project when it is saved.</p>


```csharp
protected virtual Task OnWriteSettingsAsync(ModuleSettingsWriter settings)
```
### PasteAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the Paste command is executed.</p>


```csharp
protected virtual Task PasteAsync()
```
### PasteSpecialAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">Called when the PasteSpecial command is executed.</p>


```csharp
protected virtual Task PasteSpecialAsync()
```
### Uninitialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Module.yml" sourcestartlinenumber="1">When overridden in a derived class, gives the custom Module a chance to uninitialize itself.</p>


```csharp
protected virtual void Uninitialize()
```


