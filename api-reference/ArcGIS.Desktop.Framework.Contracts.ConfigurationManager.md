# ConfigurationManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Use a ConfigurationManager to create a custom ArcGIS Pro user experience.</p>


## Object Signature

```csharp
public class ConfigurationManager
```

## Remarks

<p>
     Besides having all the capabilities of an add-in, configurations give developers many 
     additional customization opportunities to give ArcGIS Pro a custom look and feel. For 
     example, a configuration can show a custom splash screen and a custom start page; it can 
     inject business logic into the startup sequence including license checking; it can alter 
     the ribbon layout; and, like an add-in, it can introduce new functionality like modules 
     and buttons. A configuration can also control add-ins by setting the add-in security level and 
     specifying additional folders to probe for add-ins. Configurations can also block the customize
     dialog from appearing in the application options so user's can't modify the configuration.
     </p>
<p>
     With these additional extensibility points, a configuration can, for example, use role based 
     logic to present a more appropriate user interface and workflow based on the currently logged in user.
     </p>
<p>
     Declaring Configurations in DAML:
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="18"> &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;&lt;Configuration blockCustomizeDialog=&quot;true&quot; blockPerfMeter=&quot;true&quot; checkForUpdatesAtStartup=&quot;false&quot;&gt;
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="19">&lt;ConfigurationManager className = &quot;ConfigurationManager1&quot; /&gt;
&lt;AddIns securityLevel=&quot;1&quot;&gt;
&lt;AdditionalWellKnownFolder&gt;\NetworkShare\public\add-ins&lt;/AdditionalWellKnownFolder&gt;
&lt;/AddIns&gt;
&lt;/Configuration&gt;</p>
<p>
<table><thead><tr><th class="term">DAML attributes</th></tr></thead><tbody><tr><td class="term">blockCustomizeDialog</td><td class="description">Hides the customize dialog.</td></tr><tr><td class="term">blockPerfMeter</td><td class="description">Blocks the performance meter.</td></tr><tr><td class="term">checkForUpdatesAtStartup</td><td class="description">Prevents the application from checking for updates.</td></tr></tbody></table>



## Members

### ConfigurationManager()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Use a ConfigurationManager to create a custom ArcGIS Pro user experience.</p>


```csharp
public ConfigurationManager()
```
### ApplicationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Gets the new application name for the configuration.</p>


```csharp
protected virtual string ApplicationName { get; }
```
### Icon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Gets the new application icon for the configuration.</p>


```csharp
protected virtual ImageSource Icon { get; }
```
### OnApplicationInitializing(CancelEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Called when the application is initializing. It is safe to communicate with Portal at this time. The
DAML records have not been processed at this point.</p>


```csharp
protected virtual void OnApplicationInitializing(CancelEventArgs cancelEventArgs)
```
### OnApplicationReady()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Called when the appliation has fully initialized.</p>


```csharp
protected virtual void OnApplicationReady()
```
### OnCanExecuteCommand(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Gives a configuration the ability to disable commands.</p>


```csharp
protected virtual bool OnCanExecuteCommand(string cmdID, string moduleID)
```
### OnCreateDaml()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Opportunity for the configuration to provide DAML at run-time.</p>


```csharp
protected virtual string OnCreateDaml()
```
### OnCreateQuickAccessToolbar()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">The list of commands to show in the quick access toolbar.</p>


```csharp
protected virtual List<Tuple<string, bool>> OnCreateQuickAccessToolbar()
```
### OnExecuteCommand(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Allows a configuration to reject a command's execution.</p>


```csharp
protected virtual bool OnExecuteCommand(string cmdID, string moduleID)
```
### OnShowAboutPage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Allows the configuration to inject some custom user interface into the about page.</p>


```csharp
protected virtual FrameworkElement OnShowAboutPage()
```
### OnShowSplashScreen()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">The custom splash screen for the configuration.</p>


```csharp
protected virtual Window OnShowSplashScreen()
```
### OnShowStartPage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">The custom start page (landing page) to show once the appliation starts.</p>


```csharp
protected virtual FrameworkElement OnShowStartPage()
```
### OnShowWebHelp(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Called when web help is requested.</p>


```csharp
protected virtual bool OnShowWebHelp(string helpContextID)
```
### OnUpdateDatabase(XDocument)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">The last chance for the configuration to manipulate the DAML before it is processed.</p>


```csharp
protected virtual void OnUpdateDatabase(XDocument database)
```
### OnValidateLicense()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Gives the configuration the chance to perform its own license checking. Returning false
signals a licensing problem has occurred and the application should shut down.</p>


```csharp
protected virtual bool OnValidateLicense()
```
### RuntimeDamlFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Opportunity for the configuration to provide DAML file at run-time.</p>


```csharp
protected virtual string RuntimeDamlFile { get; }
```
### SkipStartPage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Return true to skip showing a start page at startup.</p>


```csharp
protected virtual bool SkipStartPage { get; }
```
### TitleBarText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.yml" sourcestartlinenumber="1">Gets the title bar text. The default implementation returns the Title unless it is empty in which case Name is used.</p>


```csharp
protected virtual string TitleBarText { get; }
```


