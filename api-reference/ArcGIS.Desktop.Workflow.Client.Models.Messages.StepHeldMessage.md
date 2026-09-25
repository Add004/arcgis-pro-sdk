# StepHeldMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The message returned when one or more steps are on hold on a job. If step is on a scheduled hold, the message also returns the scheduled release timestamp.</p>


## Object Signature

```csharp
public class StepHeldMessage : JobMessage
```


## Members

### Dependency

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">A boolean indicating whether there is a dependency on the list of steps</p>


```csharp
public bool Dependency { get; }
```
### DependencyDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The details of the job dependency. This property is only present if the dependency is a job dependency.</p>


```csharp
public StepHeldJobDependencyDetails? DependencyDetails { get; }
```
### HoldIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The ids of the holds or dependencies.</p>


```csharp
public string[]? HoldIds { get; }
```
### Manual

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">A boolean indicating whether there is a manual hold.</p>


```csharp
public bool Manual { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The message type.</p>


```csharp
public override MessageType MessageType { get; }
```
### ScheduledRelease

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The Datetime indicating when a hold will be released if scheduled.</p>


```csharp
public DateTime? ScheduledRelease { get; }
```
### SetBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The user who set the hold.</p>


```csharp
public string SetBy { get; }
```
### SetDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The date/time that the hold was set.</p>


```csharp
public DateTime? SetDate { get; }
```
### StepIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">A list of step ids on hold.</p>


```csharp
public string[] StepIds { get; }
```
### WebhookDependency

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">A boolean indicating whether there is a webhook dependency.</p>


```csharp
public bool WebhookDependency { get; }
```
### WebhookDependencyDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldMessage.yml" sourcestartlinenumber="1">The details of the webhook dependency. This property is only present if the dependency is a webhook dependency.</p>


```csharp
public WebhookDependencyDetails? WebhookDependencyDetails { get; }
```


