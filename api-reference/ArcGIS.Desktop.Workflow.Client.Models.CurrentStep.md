# CurrentStep

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Current step of a job.</p>


## Object Signature

```csharp
public class CurrentStep
```


## Members

### CurrentStep()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Current step of a job.</p>


```csharp
public CurrentStep()
```
### AssignedTo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">User or group the step is assigned to. Not used when AssignedType=Unassigned.</p>


```csharp
public string AssignedTo { get; }
```
### AssignedType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Assignment type.</p>


```csharp
public AssignedType AssignedType { get; }
```
### CanSkip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Indicates whether the step can be completed without it first being run.</p>


```csharp
public bool CanSkip { get; }
```
### Dependencies

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Indicates there are dependencies for the step.</p>


```csharp
public bool Dependencies { get; }
```
### HoldScheduledRelease

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">The release date for a scheduled hold.</p>


```csharp
public DateTime? HoldScheduledRelease { get; }
```
### ManualHold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Indicates that there is a manual hold on the step.</p>


```csharp
public bool ManualHold { get; }
```
### StepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Step id.</p>


```csharp
public string StepId { get; }
```
### StepName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.CurrentStep.yml" sourcestartlinenumber="1">Step name.</p>


```csharp
public string StepName { get; }
```


