# StepProgressMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">The step progress message</p>


## Object Signature

```csharp
public class StepProgressMessage : JobMessage
```


## Members

### AllowedActions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">The allowed actions a user can take for this step</p>


```csharp
public AllowedActions AllowedActions { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public override MessageType MessageType { get; }
```
### Msg

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">The message</p>


```csharp
public string Msg { get; }
```
### MsgCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">The message code</p>


```csharp
public string MsgCode { get; }
```
### StepIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">A list of the step ids</p>


```csharp
public string[] StepIds { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepProgressMessage.yml" sourcestartlinenumber="1">Convert the message to it's string representation</p>


```csharp
public override string ToString()
```


