# WorkflowClientModule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.WorkflowClientModule.yml" sourcestartlinenumber="1">Represents the core of the Workflow Manager system.</p>


## Object Signature

```csharp
public sealed class WorkflowClientModule : Module
```


## Members

### IsConnected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.WorkflowClientModule.yml" sourcestartlinenumber="1">Gets whether the module is connected to a Workflow Manager Server instance.</p>


```csharp
public static bool IsConnected { get; }
```
### ItemId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.WorkflowClientModule.yml" sourcestartlinenumber="1">Gets the Id of the Workflow Manager item associated with the Workflow Manager connection.</p>


```csharp
public static string ItemId { get; }
```
### JobsManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.WorkflowClientModule.yml" sourcestartlinenumber="1">Get the manager class for all Job-related functionality.</p>


```csharp
public static IJobsManager JobsManager { get; }
```
### NotificationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.WorkflowClientModule.yml" sourcestartlinenumber="1">Get a new instance of the manager class for all notification related functionality.</p>


```csharp
public static INotificationManager NotificationManager { get; }
```
### ServerUrl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.WorkflowClientModule.yml" sourcestartlinenumber="1">Gets the server url of the Workflow Manager connection.</p>


```csharp
public static string ServerUrl { get; }
```


