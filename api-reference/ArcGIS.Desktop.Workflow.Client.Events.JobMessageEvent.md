# JobMessageEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEvent.yml" sourcestartlinenumber="1">The job message event.</p>
<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEvent.yml" sourcestartlinenumber="3">Provides event information for job and step events.</p>


## Object Signature

```csharp
public sealed class JobMessageEvent : CompositePresentationEvent<JobMessageEventArgs<JobMessage>>
```


## Members

### Subscribe(Action&lt;JobMessageEventArgs&lt;JobMessage&gt;&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEvent.yml" sourcestartlinenumber="1">A method called to subscribe to the message event.</p>


```csharp
public static SubscriptionToken Subscribe(Action<JobMessageEventArgs<JobMessage>> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEvent.yml" sourcestartlinenumber="1">A method to unsubscribe from the message event.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;JobMessageEventArgs&lt;JobMessage&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEvent.yml" sourcestartlinenumber="1">A method to unsubscribe from the message event.</p>


```csharp
public static void Unsubscribe(Action<JobMessageEventArgs<JobMessage>> action)
```


