# OpenProProjectItemsStepInfoRequiredMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The open pro project items step info required message</p>


## Object Signature

```csharp
public class OpenProProjectItemsStepInfoRequiredMessage : StepInfoRequiredMessage
```


## Members

### ActiveVersions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A list of active versions</p>


```csharp
public WorkflowJobVersion[] ActiveVersions { get; }
```
### CloseProProject

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether to close the pro project when the step is finished</p>


```csharp
public bool? CloseProProject { get; }
```
### ErrorInspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether to open the error inspector as set in the step configuration</p>


```csharp
public bool ErrorInspector { get; }
```
### OpenProItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A list of the pro items that are to be opened</p>


```csharp
public ProItem[] OpenProItems { get; }
```
### ProCommands

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A list of pro commands to be executed</p>


```csharp
public string[] ProCommands { get; }
```
### ProjectInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The project information</p>


```csharp
public ProjectInfo ProjectInfo { get; }
```
### RestrictEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The restrict edits parameters</p>


```csharp
public RestrictEdits RestrictEdits { get; }
```
### SynchronizeReplica

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The synchronize replica options</p>


```csharp
public SynchronizeReplicaOptions SynchronizeReplica { get; }
```
### UserPrompt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The user prompt as defined in the step</p>


```csharp
public string UserPrompt { get; }
```
### ZoomToLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.OpenProProjectItemsStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether to zoom to the location</p>


```csharp
public bool ZoomToLocation { get; }
```


