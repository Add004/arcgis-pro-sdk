# StepHeldWebhookDependency

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.Messages.html">Messages</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldWebhookDependency.yml" sourcestartlinenumber="1">Additional webhook dependency info for a step hold message.</p>


## Object Signature

```csharp
public class StepHeldWebhookDependency
```


## Members

### WebhookLayerId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldWebhookDependency.yml" sourcestartlinenumber="1">The layer id of the associated record for this webhook dependency.</p>


```csharp
public int WebhookLayerId { get; }
```
### WebhookObjectId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldWebhookDependency.yml" sourcestartlinenumber="1">The object id of the associated record for this webhook dependency.</p>


```csharp
public long WebhookObjectId { get; }
```
### WebhookReleaseCondition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.Messages.StepHeldWebhookDependency.yml" sourcestartlinenumber="1">A where clause defining the conditions for webhook release. Can contain multiple clauses.</p>


```csharp
public string WebhookReleaseCondition { get; }
```


