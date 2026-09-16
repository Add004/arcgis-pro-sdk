# JobAttachmentUpdatedMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobAttachmentUpdatedMessage.yml" sourcestartlinenumber="1">The job attachment updated message</p>


## Object Signature

```csharp
public class JobAttachmentUpdatedMessage : JobMessage
```


## Members

### Adds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobAttachmentUpdatedMessage.yml" sourcestartlinenumber="1">A list representing the job attachments that were added</p>


```csharp
public List<JobAttachmentDescription> Adds { get; }
```
### Deletes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobAttachmentUpdatedMessage.yml" sourcestartlinenumber="1">A list representing the job attachments taht were deleted</p>


```csharp
public List<string> Deletes { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobAttachmentUpdatedMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public override MessageType MessageType { get; }
```
### Updates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobAttachmentUpdatedMessage.yml" sourcestartlinenumber="1">A list representing the job attachments that were updated</p>


```csharp
public List<JobAttachmentDescription> Updates { get; }
```


