# UpdateJobPropertiesStepInfoRequiredMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdateJobPropertiesStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The update job properties step info required message
for job extended and one-to-many properties</p>


## Object Signature

```csharp
public class UpdateJobPropertiesStepInfoRequiredMessage : StepInfoRequiredMessage
```


## Members

### JobTemplateId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdateJobPropertiesStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The job template id</p>


```csharp
public string JobTemplateId { get; }
```
### Prompt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdateJobPropertiesStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The prompt</p>


```csharp
public string Prompt { get; }
```
### Properties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdateJobPropertiesStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The list of properties to update</p>


```csharp
public UpdateJobPropertyDetails[] Properties { get; }
```
### StepMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdateJobPropertiesStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The step mode for one-to-many properties</p>


```csharp
public StepMode StepMode { get; }
```
### UserPrompt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdateJobPropertiesStepInfoRequiredMessage.yml" sourcestartlinenumber="1">The user prompt as defined in the step</p>


```csharp
public string UserPrompt { get; }
```


