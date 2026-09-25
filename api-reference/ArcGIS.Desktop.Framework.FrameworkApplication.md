# FrameworkApplication

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Encapsulates the ArcGISPro application.</p>


## Object Signature

```csharp
public class FrameworkApplication : Application, IQueryAmbient
```

## Remarks

<p>
    The FrameworkApplication object is the central object in the Framework API. Its main purpose is to pull together all of the extensions
    and add-ins into one application. The FrameworkApplication encapsulates application-specific functionality, including the following::
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="5">&lt;ul&gt;&lt;li&gt;Access to the modules, commands, backstage, panes, and dock panes.&lt;/li&gt;&lt;li&gt;The application state.&lt;/li&gt;&lt;li&gt;The event aggregator.&lt;/li&gt;&lt;li&gt;Customization filters.&lt;/li&gt;&lt;li&gt;Custom drop handlers.&lt;/li&gt;&lt;li&gt;Notifications.&lt;/li&gt;&lt;li&gt;The help system.&lt;/li&gt;&lt;/ul&gt;&lt;/p&gt;
</code></pre>
<p>
    The FrameworkApplication class follows the singleton pattern to provide easy access to its functionality.
    </p>


## Members

### ActivateTab(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Activates the specified ribbon tab.</p>


```csharp
public static void ActivateTab(string id)
```
### ActivateWindow()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Focuses the main window.</p>


```csharp
public static void ActivateWindow()
```
### ActiveTab

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the DAML identifier of the currently active ribbon tab.</p>


```csharp
public static string ActiveTab { get; }
```
### ActiveTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the application's current tool. Only one tool is active at a time.</p>


```csharp
public static Tool ActiveTool { get; }
```
### ActiveWindow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Framework.Contracts.Pane" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane" data-throw-if-not-resolved="false"></xref> that is currently active.</p>


```csharp
public static IFrameworkWindow ActiveWindow { get; }
```
### AddNotification(Notification)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Presents a notification.</p>


```csharp
public static void AddNotification(Notification notification)
```
### ApplicationProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the application properties.</p>


```csharp
public static ApplicationProperties ApplicationProperties { get; }
```
### ApplicationTheme

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets the application's theme that dictates its visual style. Three themes are supported: default (metro), dark, and high contrast.</p>


```csharp
public static ApplicationTheme ApplicationTheme { get; set; }
```
### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Closes the application.</p>


```csharp
public static void Close()
```
### CloseBackstage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Closes the backstage.</p>


```csharp
public static void CloseBackstage()
```
### ContextMenuDataContext

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the contextual data that is passed to the commands in a context menu.</p>


```csharp
public static object ContextMenuDataContext { get; }
```
### ContextMenuDataContextAs&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the contextual data as the requested type T. Contextual data represents the selected item (or items) that is passed
to a command when executing that command on a context menu.</p>


```csharp
public static T ContextMenuDataContextAs<T>() where T : class
```
### ContextMenuDataContextViewModel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the current context menu's default data context as a view-model. This is for Esri internal use only.</p>


```csharp
public static object ContextMenuDataContextViewModel { get; }
```
### CreateContextMenu(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Creates a WPF context menu.</p>


```csharp
public static ContextMenu CreateContextMenu(IEnumerable<string> menuIDs)
```
### CreateContextMenu(string, Func&lt;object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Creates a WPF context menu.</p>


```csharp
public static ContextMenu CreateContextMenu(string menuID, Func<object> property = null)
```
### CreateContextMenu(string, string, Func&lt;object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Creates a WPF context menu.</p>


```csharp
public static ContextMenu CreateContextMenu(string menuID, string toolbarID, Func<object> property = null)
```
### CurrentTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets the application's current tool. Only one tool is active at a time.</p>


```csharp
public static string CurrentTool { get; set; }
```
### DDEExecuteCommand(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">This is for Esri internal use only.</p>


```csharp
protected virtual bool DDEExecuteCommand(string topic, string commandString)
```
### DDEIsTopicSupported(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">This is for Esri internal use only.</p>


```csharp
protected virtual bool DDEIsTopicSupported(string topic)
```
### DockPaneManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets all the active dockpane instances; this singleton also lets
you activate, create, and close dockpanes.</p>


```csharp
public static DockPaneManager DockPaneManager { get; }
```
### EventAggregator

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the application's event aggregator.</p>


```csharp
public static IEventAggregator EventAggregator { get; }
```
### ExecuteCommand(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Obtains a function that can be used to execute the specified command.</p>


```csharp
public static Func<Task> ExecuteCommand(string id)
```
### ExecuteCommandArgs(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Obtains a function that can be used to execute the specified command with arguments.</p>


```csharp
public static Func<object[], Task> ExecuteCommandArgs(string id)
```
### FindModule(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Returns the specified module; the module is loaded if necessary.</p>


```csharp
public static Module FindModule(string id)
```
### FloatingWindowName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the default floating window name.</p>


```csharp
public static string FloatingWindowName { get; }
```
### FlowDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the content flow direction for text and user interface elements.</p>


```csharp
public static FlowDirection FlowDirection { get; }
```
### GetAddInInfos()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Returns a collection of AddInfos representing the currently loaded add-ins.</p>


```csharp
public static List<AddInInfo> GetAddInInfos()
```
### GetPlugInWrapper(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Returns a run-time wrapper around the specified DAML component.</p>


```csharp
public static IPlugInWrapper GetPlugInWrapper(string id, bool create = true)
```
### HideMiniToolbar()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Hides all minitoolbars.</p>


```csharp
public static void HideMiniToolbar()
```
### Icon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">The main application window's icon.</p>


```csharp
protected virtual ImageSource Icon { get; }
```
### IncomingTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the Incoming tool.  This is set when <xref href="ArcGIS.Desktop.Framework.FrameworkApplication.SetCurrentToolAsync(System.String)" data-throw-if-not-resolved="false"></xref> is called.</p>


```csharp
public static string IncomingTool { get; }
```
### Initialized

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets true once the application shell has been loaded and a license has been acquired.</p>


```csharp
public static bool Initialized { get; }
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets whether the application is the active application.</p>


```csharp
public static bool IsActive { get; }
```
### IsBackstageOpen

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets whether the application backstage is open.</p>


```csharp
public static bool IsBackstageOpen { get; }
```
### IsBusy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets a boolean value of true indicating the application is currently busy.</p>


```csharp
public static bool IsBusy { get; }
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the application's user interface is currently enabled.</p>


```csharp
public static bool IsEnabled { get; set; }
```
### IsRibbonMinimized

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets whether the ribbon is currently minimized.</p>


```csharp
public static bool IsRibbonMinimized { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets the application's name which is displayed in the application's title bar. Note, the title bar will switch to the Title property
if it is not empty.</p>


```csharp
public static string Name { get; set; }
```
### NotificationInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Define the time span in seconds for showing the same notification to limit the toast display frequency.</p>


```csharp
public static int NotificationInterval { get; set; }
```
### OpenBackstage(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Opens the backstage.</p>


```csharp
public static void OpenBackstage(string id = "")
```
### OutgoingTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the Outgoing tool. This is set when <xref href="ArcGIS.Desktop.Framework.FrameworkApplication.SetCurrentToolAsync(System.String)" data-throw-if-not-resolved="false"></xref> is called.</p>


```csharp
public static string OutgoingTool { get; }
```
### Panes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets all the active pane instances; this singleton also lets you
activate, create, and close panes.</p>


```csharp
public static PaneCollection Panes { get; }
```
### QueueIdleAction(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Queues an action that will be performed when the application next
enters an idle state where the user is not interacting with a modal
dialog or performing any activity that might conflict with the specified action.</p>


```csharp
public static void QueueIdleAction(Action action)
```
### RegisterCustomizationFilter(CustomizationFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Adds the supplied customization filter to the application's customization model.</p>


```csharp
public static bool RegisterCustomizationFilter(CustomizationFilter filter)
```
### RemoveNotification(Notification)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Removes the specified notification.</p>


```csharp
public static void RemoveNotification(Notification notification)
```
### ScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Get or sets the current user interface scaling factor.</p>


```csharp
public static double ScaleFactor { get; set; }
```
### SetCurrentToolAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Activates the specified tool.</p>


```csharp
public static Task SetCurrentToolAsync(string id)
```
### ShowHelpTopic(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Shows the help topic associated with the specified helpContextID.</p>


```csharp
public static void ShowHelpTopic(string helpContextID)
```
### ShowWizard(string, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Opens the specified wizard.</p>


```csharp
public static bool? ShowWizard(string id, object data)
```
### ShutdownAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Try to shut down the application.</p>


```csharp
public static Task<bool> ShutdownAsync()
```
### ShutdownAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Try to shut down the application.</p>


```csharp
public static Task<bool> ShutdownAsync(bool restart)
```
### Spell_SetLanguage(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Sets the spell check language.</p>


```csharp
[Obsolete]
public static extern void Spell_SetLanguage(string language)
```
### State

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets the application's state object.</p>


```csharp
public static State State { get; }
```
### SubTitle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets the application's SubTitle.</p>


```csharp
public static string SubTitle { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets the application's Title.</p>


```csharp
public static string Title { get; set; }
```
### TitleBarImageSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Gets or sets the application's Titlbar image when the title has a popup.</p>


```csharp
public static ImageSource TitleBarImageSource { get; set; }
```
### UnregisterCustomizationFilter(CustomizationFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Removes the specified customization filter from the application's customization model.</p>


```csharp
public static void UnregisterCustomizationFilter(CustomizationFilter filter)
```
### UpdateTheme(ThemeIntent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.FrameworkApplication.yml" sourcestartlinenumber="1">Allow applications to modify the theming.</p>


```csharp
protected virtual void UpdateTheme(ThemeIntent themeIntent)
```


