# StepState

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">The state of a step</p>


## Object Signature

```csharp
public class StepState
```


## Members

### StepState()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">The state of a step</p>


```csharp
public StepState()
```
### AssignedTo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">The user or group the step is assigned to</p>


```csharp
public string AssignedTo { get; }
```
### AssignedType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">The assignment type</p>


```csharp
public AssignedType AssignedType { get; }
```
### CanSkip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">A boolean indicating whether the step can be skipped</p>


```csharp
public bool CanSkip { get; }
```
### MessageDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">Details about the current running step. This message is
one of the step execution status messages including StepInfoRequired,
StepStarted, StepProgress, StepStopping, StepStopped, StepWarningStopped,
StepPaused, StepCancelled, StepHeld, StepError messages. The StepFinished message
will not be included. StepInfoRequired messages will
be truncated for users other than the assigned user.</p>


```csharp
public JobMessage MessageDetails { get; }
```
### StepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">The step id</p>


```csharp
public string StepId { get; }
```
### StepName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.StepState.yml" sourcestartlinenumber="1">The step name</p>


```csharp
public string StepName { get; }
```


