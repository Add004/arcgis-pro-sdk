# StepHoldReleasedMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldReleasedMessage.yml" sourcestartlinenumber="1">The message returned when a step hold or dependency has been released on a job. If there are multiple holds or
dependencies on a step, this message will only be sent when all holds and dependencies have been released.</p>


## Object Signature

```csharp
public class StepHoldReleasedMessage : JobMessage
```


## Members

### HoldIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldReleasedMessage.yml" sourcestartlinenumber="1">The ids of the holds or dependencies.</p>


```csharp
public string[]? HoldIds { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldReleasedMessage.yml" sourcestartlinenumber="1">The message type.</p>


```csharp
public override MessageType MessageType { get; }
```
### ReleasedBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldReleasedMessage.yml" sourcestartlinenumber="1">The user who released the  hold or dependency.</p>


```csharp
public string ReleasedBy { get; }
```
### ReleasedDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldReleasedMessage.yml" sourcestartlinenumber="1">The date/time when the hold or dependency was released.</p>


```csharp
public DateTime? ReleasedDate { get; }
```
### StepIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHoldReleasedMessage.yml" sourcestartlinenumber="1">A list of the step ids.</p>


```csharp
public string[] StepIds { get; }
```


