# JobMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobMessage.yml" sourcestartlinenumber="1">Base class for all job and step messages</p>


## Object Signature

```csharp
public abstract class JobMessage
```


## Members

### JobMessage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobMessage.yml" sourcestartlinenumber="1">Base class for all job and step messages</p>


```csharp
protected JobMessage()
```
### JobId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobMessage.yml" sourcestartlinenumber="1">The job id</p>


```csharp
public string JobId { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.JobMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public abstract MessageType MessageType { get; }
```


