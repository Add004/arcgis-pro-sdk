# ReportsModule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Represents the reports module.</p>


## Object Signature

```csharp
public sealed class ReportsModule : Module
```

## Remarks

<p>
    Modules are what make the framework system extensible.  The framework loads modules and when your module loads, everything in it loads as well, for example, 
    commands, widgets, a custom about panel, and so on.
    </p>
<p> 
    The ONLY member that you can use is <xref href="ArcGIS.Desktop.Internal.Reports.ReportsModule.Current?text=Current" data-throw-if-not-resolved="false"></xref>.  The API reference help displays many more protected 
    members that are inherited from <xref href="ArcGIS.Desktop.Framework.Contracts.Module" data-throw-if-not-resolved="false"></xref> but these are not available to the report module. They would only be 
    accessible if you were to create your own custom module.
    </p>


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Returns a reference to the current report module in the application.  There is only one report module.</p>


```csharp
public static ReportsModule Current { get; }
```
### Initialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by framework to initialize the report module.</p>


```csharp
protected override bool Initialize()
```
### OnPaneActivated(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by the Framework when a Pane is activated.</p>


```csharp
protected override void OnPaneActivated(Pane incomingPane)
```
### OnPaneClosed(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by the Framework when a Pane is closed.</p>


```csharp
protected override void OnPaneClosed(Pane pane)
```
### OnPaneClosing(Pane, CancelRoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by the Framework when one of the Module's Pane is about to close.</p>


```csharp
protected override void OnPaneClosing(Pane pane, CancelRoutedEventArgs e)
```
### OnPaneDeactivated(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by the Framework when a Pane is deactivated.</p>


```csharp
protected override void OnPaneDeactivated(Pane outgoingPane)
```
### OnPaneOpened(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by the Framework when a new Pane is opened. This occurs after the pane has been fully initialized.</p>


```csharp
protected override void OnPaneOpened(Pane pane)
```
### Uninitialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportsModule.yml" sourcestartlinenumber="1">Called by the framework to uninitialize the report module.</p>


```csharp
protected override void Uninitialize()
```


