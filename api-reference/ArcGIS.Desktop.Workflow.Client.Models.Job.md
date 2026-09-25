# Job

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">A job in the Workflow Manager system.</p>


## Object Signature

```csharp
public class Job
```


## Members

### Job()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">A job in the Workflow Manager system.</p>


```csharp
public Job()
```
### ActiveVersions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">The active versions available on the job.</p>


```csharp
public WorkflowJobVersion[] ActiveVersions { get; }
```
### ClosedBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">The user name of the user who closed the job.</p>


```csharp
public string ClosedBy { get; }
```
### CurrentSteps

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Current steps of the job.</p>


```csharp
public List<CurrentStep> CurrentSteps { get; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job description.</p>


```csharp
public string Description { get; }
```
### DueDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job due date.</p>


```csharp
public DateTime? DueDate { get; }
```
### ExtendedProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Extended properties of the job with a relationship type of one-to-one. Jobs can only have one value for the properties in the extended properties table.</p>


```csharp
public List<ExtendedPropertyTable> ExtendedProperties { get; }
```
### Holds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Active holds on the job.</p>


```csharp
public List<JobHold> Holds { get; }
```
### JobId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job id.</p>


```csharp
public string JobId { get; }
```
### JobName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job name.</p>


```csharp
public string JobName { get; }
```
### JobStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job status.</p>


```csharp
public string JobStatus { get; }
```
### JobTemplateId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Id of the job template the job was created from.</p>


```csharp
public string JobTemplateId { get; }
```
### JobTemplateName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Name of the job template the job was created from.</p>


```csharp
public string JobTemplateName { get; }
```
### Notes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job notes.</p>


```csharp
public string Notes { get; }
```
### OwnedBy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Username of the user who owns the job.</p>


```csharp
public string OwnedBy { get; }
```
### ParentJobId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job id of the parent job.</p>


```csharp
public string ParentJobId { get; }
```
### Priority

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job priority.</p>


```csharp
public string Priority { get; }
```
### RelatedProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Related properties of the job with a relationship type of one-to-many. Jobs can have multiple values for the properties in the related properties table.</p>


```csharp
public List<RelatedPropertyTable> RelatedProperties { get; }
```
### StartDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Job.yml" sourcestartlinenumber="1">Job start date.</p>


```csharp
public DateTime? StartDate { get; }
```


