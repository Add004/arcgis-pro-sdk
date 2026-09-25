# ProGPStepInfoRequiredMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The pro gp step info requied notification message</p>


## Object Signature

```csharp
public class ProGPStepInfoRequiredMessage : StepInfoRequiredMessage
```


## Members

### GPLogAttachmentFolder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The gp log attachment folder</p>


```csharp
public string GPLogAttachmentFolder { get; }
```
### IsGPLogAttached

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether the gp log is attached</p>


```csharp
public bool IsGPLogAttached { get; }
```
### Parameters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A list of parameters for the gp step</p>


```csharp
public List<NameValuePair> Parameters { get; }
```
### ToolName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The tool name</p>


```csharp
public string ToolName { get; }
```
### Toolbox

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The toolbox name</p>


```csharp
public string Toolbox { get; }
```
### ToolboxType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The pro toolbox type</p>


```csharp
public ProToolboxType ToolboxType { get; }
```
### UserPrompt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The user prompt as defined in the step</p>


```csharp
public string UserPrompt { get; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.ProGPStepInfoRequiredMessage.yml" sourcestartlinenumber="1">A boolean indicating whether the step should be visible</p>


```csharp
public bool Visible { get; }
```


