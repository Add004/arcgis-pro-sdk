# DefineLocationStepInfoResponseMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.DefineLocationStepInfoResponseMessage.yml" sourcestartlinenumber="1">The define location step response message</p>


## Object Signature

```csharp
public class DefineLocationStepInfoResponseMessage : StepInfoResponseMessage
```


## Members

### DefineLocationStepInfoResponseMessage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.DefineLocationStepInfoResponseMessage.yml" sourcestartlinenumber="1">The define location step response message</p>


```csharp
public DefineLocationStepInfoResponseMessage()
```
### Failed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.DefineLocationStepInfoResponseMessage.yml" sourcestartlinenumber="1">A boolean indicating whether the step failed</p>


```csharp
public bool Failed { get; set; }
```
### Location

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.DefineLocationStepInfoResponseMessage.yml" sourcestartlinenumber="1">The updated location for the step resposne. The response is a json string representation of a Geometry object.</p>


```csharp
public string Location { get; set; }
```


