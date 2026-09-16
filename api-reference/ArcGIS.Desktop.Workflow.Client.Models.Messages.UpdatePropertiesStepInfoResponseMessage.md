# UpdatePropertiesStepInfoResponseMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdatePropertiesStepInfoResponseMessage.yml" sourcestartlinenumber="1">The updated property response message for the following steps:
UpdateJobProperties
UpdateJobProperties1M (one-to-many properties)
ProGP
ExecuteGP</p>


## Object Signature

```csharp
public class UpdatePropertiesStepInfoResponseMessage : StepInfoResponseMessage
```


## Members

### UpdatePropertiesStepInfoResponseMessage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdatePropertiesStepInfoResponseMessage.yml" sourcestartlinenumber="1">The updated property response message for the following steps:
UpdateJobProperties
UpdateJobProperties1M (one-to-many properties)
ProGP
ExecuteGP</p>


```csharp
public UpdatePropertiesStepInfoResponseMessage()
```
### Comment

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdatePropertiesStepInfoResponseMessage.yml" sourcestartlinenumber="1">The comment added in a Update property step</p>


```csharp
public string Comment { get; set; }
```
### PropertyResponses

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.UpdatePropertiesStepInfoResponseMessage.yml" sourcestartlinenumber="1">The list of property responses</p>


```csharp
public PropertyResponse[] PropertyResponses { get; set; }
```


