# INotificationManager

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="1">Provides access to job and step notifications within Workflow Manager.</p>


## Object Signature

```csharp
public interface INotificationManager
```


## Members

### SendStepResponse(StepResponse)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="1">Send a response to Workflow Manager Server pertaining to a job's current step.</p>
<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="3">The response must include the jobId, stepId, and other information pertinent to the step.</p>


```csharp
void SendStepResponse(StepResponse response)
```
### SubscribeToJobs(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="1">Subscribe to messages for the given jobs.</p>


```csharp
void SubscribeToJobs(List<string> jobIds)
```
### SubscriberId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="1">The id used to subscribe to jobs.</p>
<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="3">This id is returned as part of the JobState message to identify which sender
initiated the job subscription.</p>


```csharp
string SubscriberId { get; }
```
### UnsubscribeFromJobs(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.INotificationManager.yml" sourcestartlinenumber="1">Unsubscribe to messages for the given jobs.</p>


```csharp
void UnsubscribeFromJobs(List<string> jobIds)
```


