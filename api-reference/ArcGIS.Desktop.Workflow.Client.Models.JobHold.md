# JobHold

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Hold information for a job.</p>


## Object Signature

```csharp
public class JobHold
```


## Members

### JobHold()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Hold information for a job.</p>


```csharp
public JobHold()
```
### DependentJobId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Job id of a dependent job.</p>


```csharp
public string? DependentJobId { get; }
```
### DependentStepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Step id of the dependent job.</p>


```csharp
public string? DependentStepId { get; }
```
### HoldId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Hold id.</p>


```csharp
public string HoldId { get; }
```
### JobId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Job id.</p>


```csharp
public string JobId { get; }
```
### ReleasedBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">User that released the hold.</p>


```csharp
public string? ReleasedBy { get; }
```
### ReleasedDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Date when hold was released.</p>


```csharp
public DateTime? ReleasedDate { get; }
```
### ScheduledRelease

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Release date for a scheduled hold.</p>


```csharp
public DateTime? ScheduledRelease { get; }
```
### SetBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">User that added the hold.</p>


```csharp
public string SetBy { get; }
```
### SetDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Date when hold was set.</p>


```csharp
public DateTime SetDate { get; }
```
### StepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Step id.</p>


```csharp
public string StepId { get; }
```
### WebhookConnectionId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Webhook connection Id associated with a webhook dependency.</p>


```csharp
public string? WebhookConnectionId { get; }
```
### WebhookDependency

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.JobHold.yml" sourcestartlinenumber="1">Webhook dependency information object.</p>


```csharp
public WebhookDependency? WebhookDependency { get; }
```


