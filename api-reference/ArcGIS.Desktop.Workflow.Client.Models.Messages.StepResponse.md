# StepResponse

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepResponse.yml" sourcestartlinenumber="1">The step response message used to send additional step information to Workflow Manager Server.</p>


## Object Signature

```csharp
public class StepResponse
```


## Members

### StepResponse()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepResponse.yml" sourcestartlinenumber="1">The step response message used to send additional step information to Workflow Manager Server.</p>


```csharp
public StepResponse()
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepResponse.yml" sourcestartlinenumber="1">The step response message. The response type is specific for each step.</p>


```csharp
public StepInfoResponseMessage Message { get; set; }
```
### MsgType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepResponse.yml" sourcestartlinenumber="1">A string representing the message type, &quot;StepInformation&quot;</p>


```csharp
public string MsgType { get; }
```


