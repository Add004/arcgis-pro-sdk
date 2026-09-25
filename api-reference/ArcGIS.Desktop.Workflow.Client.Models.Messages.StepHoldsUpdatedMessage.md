# StepHoldsUpdatedMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">This message will be sent any time a hold or dependency is added or released that does not impact step execution, which includes:
a hold or a dependency is added to a step that is already on hold,
a hold or a dependency is released from a step but it stays on hold,
a hold or a dependency is added to a step and the hold's release condition is already satisfied,
or a hold or a dependency is added or released on a future step.</p>


## Object Signature

```csharp
public class StepHoldsUpdatedMessage : JobMessage
```


## Members

### DependencyDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The details of the job dependency. This property is only present if the dependency is a job dependency.</p>


```csharp
public StepHeldJobDependencyDetails DependencyDetails { get; }
```
### HoldIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The ids of the holds or dependencies.</p>


```csharp
public string[] HoldIds { get; }
```
### Manual

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">Indicates whether the hold was applied manually.</p>


```csharp
public bool? Manual { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The message type.</p>


```csharp
public override MessageType MessageType { get; }
```
### ReleasedBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The user who released the  hold or dependency.</p>


```csharp
public string ReleasedBy { get; }
```
### ReleasedDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The date/time when the hold or dependency was released.</p>


```csharp
public DateTime? ReleasedDate { get; }
```
### ScheduledRelease

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The date/time indicating when a hold will be released if scheduled.</p>


```csharp
public DateTime? ScheduledRelease { get; }
```
### SetBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The user who set the hold or dependency.</p>


```csharp
public string SetBy { get; }
```
### SetDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The date/time that the hold or dependency was set</p>


```csharp
public DateTime? SetDate { get; }
```
### StepIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">A list of step ids.</p>


```csharp
public string[] StepIds { get; }
```
### WebhookDependencyDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldsUpdatedMessage.yml" sourcestartlinenumber="1">The details of the webhook dependency. This property is only present if the dependency is a webhook dependency.</p>


```csharp
public WebhookDependencyDetails WebhookDependencyDetails { get; }
```


