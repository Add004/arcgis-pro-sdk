# WebhookDependency

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.WebhookDependency.yml" sourcestartlinenumber="1">Webhook dependency object.</p>


## Object Signature

```csharp
public class WebhookDependency
```


## Members

### WebhookDependency()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.WebhookDependency.yml" sourcestartlinenumber="1">Webhook dependency object.</p>


```csharp
public WebhookDependency()
```
### WebhookLayerId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.WebhookDependency.yml" sourcestartlinenumber="1">The layer id for the feature service layer used in the webhook dependency.</p>


```csharp
public int WebhookLayerId { get; }
```
### WebhookObjectId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.WebhookDependency.yml" sourcestartlinenumber="1">The object id for the feature layer record used in the webhook dependency.</p>


```csharp
public long WebhookObjectId { get; }
```
### WebhookReleaseCondition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.WebhookDependency.yml" sourcestartlinenumber="1">A where clause defining the conditions for webhook release. Can contain multiple clauses.</p>


```csharp
public string WebhookReleaseCondition { get; }
```


