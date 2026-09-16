# WorkflowConnectionChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.WorkflowConnectionChangedEvent.yml" sourcestartlinenumber="1">The workflow connection changed event.</p>


## Object Signature

```csharp
public sealed class WorkflowConnectionChangedEvent : AsyncPresentationEvent<WorkflowConnectionChangedEventArgs>
```


## Members

### Subscribe(Func&lt;WorkflowConnectionChangedEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.WorkflowConnectionChangedEvent.yml" sourcestartlinenumber="1">A method called to subscribe to the message event.</p>


```csharp
public static SubscriptionToken Subscribe(Func<WorkflowConnectionChangedEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.WorkflowConnectionChangedEvent.yml" sourcestartlinenumber="1">A method to unsubscribe from the message event.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;WorkflowConnectionChangedEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.WorkflowConnectionChangedEvent.yml" sourcestartlinenumber="1">A method to unsubscribe from the message event.</p>


```csharp
public static void Unsubscribe(Func<WorkflowConnectionChangedEventArgs, Task> action)
```


