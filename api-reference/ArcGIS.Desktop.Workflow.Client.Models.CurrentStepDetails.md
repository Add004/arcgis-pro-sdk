# CurrentStepDetails

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">Information regarding the current steps in a job</p>


## Object Signature

```csharp
public class CurrentStepDetails
```


## Members

### CurrentStepDetails()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">Information regarding the current steps in a job</p>


```csharp
public CurrentStepDetails()
```
### AssignedTo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">The user or group the step is assigned to. Not used when AssignedType=Unassigned.</p>


```csharp
public string AssignedTo { get; }
```
### AssignedType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">The assignment type</p>


```csharp
public AssignedType AssignedType { get; }
```
### CanSkip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">A boolean indicating whether the step can be skipped</p>


```csharp
public bool CanSkip { get; }
```
### Dependencies

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">A boolean indicating whether this step has job dependencies</p>


```csharp
public bool Dependencies { get; }
```
### HoldScheduledRelease

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">The Datetime indicating when a hold will be released if scheduled</p>


```csharp
public DateTime? HoldScheduledRelease { get; }
```
### ManualHold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">A boolean indicating whether this step is in a manual hold</p>


```csharp
public bool ManualHold { get; }
```
### StepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">The step id</p>


```csharp
public string StepId { get; }
```
### StepName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">The step name</p>


```csharp
public string StepName { get; }
```
### WebhookDependency

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStepDetails.yml" sourcestartlinenumber="1">A boolean indicating whether this step has a webhook dependency</p>


```csharp
public bool WebhookDependency { get; }
```


