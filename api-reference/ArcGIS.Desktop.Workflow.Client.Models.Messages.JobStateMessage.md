# JobStateMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">The job state message</p>


## Object Signature

```csharp
public class JobStateMessage : JobMessage
```


## Members

### DiagramId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">Diagram id</p>


```csharp
public string DiagramId { get; }
```
### DiagramVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">Diagram version</p>


```csharp
public long DiagramVersion { get; }
```
### JobStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">The job status</p>


```csharp
public string JobStatus { get; }
```
### JobTemplateName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">The job template name</p>


```csharp
public string JobTemplateName { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public override MessageType MessageType { get; }
```
### PercentComplete

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">Percent complete</p>


```csharp
public double PercentComplete { get; }
```
### SenderId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">The senderId provided in the NotificationManager.Subscribe method. This identifies which sender
initiated the job subscription which caused this JobState message to be sent out.</p>


```csharp
public string SenderId { get; }
```
### StepStates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobStateMessage.yml" sourcestartlinenumber="1">A list representing the states of various steps</p>


```csharp
public List<StepState> StepStates { get; }
```


