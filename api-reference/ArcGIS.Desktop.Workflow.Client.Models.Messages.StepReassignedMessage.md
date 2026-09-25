# StepReassignedMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepReassignedMessage.yml" sourcestartlinenumber="1">The step reassigned message</p>


## Object Signature

```csharp
public class StepReassignedMessage : JobMessage
```


## Members

### AssignedTo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepReassignedMessage.yml" sourcestartlinenumber="1">The user or group the step is assigned to</p>


```csharp
public string AssignedTo { get; }
```
### AssignedType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepReassignedMessage.yml" sourcestartlinenumber="1">The assignment type</p>


```csharp
public AssignedType AssignedType { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepReassignedMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public override MessageType MessageType { get; }
```
### StepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepReassignedMessage.yml" sourcestartlinenumber="1">The step id</p>


```csharp
public string StepId { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepReassignedMessage.yml" sourcestartlinenumber="1">Convert the message to it's string representation</p>


```csharp
public override string ToString()
```


