# StepInfoRequiredMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The step info required message when additional information is required
for the step to continue</p>


## Object Signature

```csharp
public class StepInfoRequiredMessage : JobMessage
```


## Members

### AllowedActions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The allowed action on the step for the user</p>


```csharp
public AllowedActions AllowedActions { get; }
```
### CanComment

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether a user can comment on this step</p>


```csharp
public bool CanComment { get; }
```
### CommentRequired

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether a comment is required for this step</p>


```csharp
public bool CommentRequired { get; }
```
### HelpLink

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The help link as defined in the step</p>


```csharp
public string HelpLink { get; }
```
### HelpText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The help text as defined in the step</p>


```csharp
public string HelpText { get; }
```
### IsInvalid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">Indicates that the message contents are invalid</p>


```csharp
public bool IsInvalid { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The message type</p>


```csharp
public override MessageType MessageType { get; }
```
### Msg

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The message</p>


```csharp
public string Msg { get; }
```
### MsgCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The message code</p>


```csharp
public string MsgCode { get; }
```
### StepId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">The step id</p>


```csharp
public string StepId { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepInfoRequiredMessage.yml" sourcestartlinenumber="1">Convert the message to it's string representation</p>


```csharp
public override string ToString()
```


