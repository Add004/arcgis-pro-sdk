# StepFinishedMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepFinishedMessage.yml" sourcestartlinenumber="1">The step finished message</p>


## Object Signature

```csharp
public class StepFinishedMessage : JobMessage
```


## Members

### CurrentSteps

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepFinishedMessage.yml" sourcestartlinenumber="1">A list of the current steps</p>


```csharp
public CurrentStepDetails[] CurrentSteps { get; }
```
### JobStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepFinishedMessage.yml" sourcestartlinenumber="1">The job status</p>


```csharp
public string JobStatus { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepFinishedMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public override MessageType MessageType { get; }
```
### StepIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepFinishedMessage.yml" sourcestartlinenumber="1">A list of step ids that finished</p>


```csharp
public string[] StepIds { get; }
```


