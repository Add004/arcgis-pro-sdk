# TaskEndedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEvent.yml" sourcestartlinenumber="1">Occurs when execution of a task ends. This occurs when a task is canceled or when a task is successfully completed.</p>


## Object Signature

```csharp
public sealed class TaskEndedEvent : CompositePresentationEvent<TaskEndedEventArgs>
```


## Members

### Subscribe(Action&lt;TaskEndedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEvent.yml" sourcestartlinenumber="1">Subscribes to TaskEndedEvents that are published when a task ends.</p>


```csharp
public static SubscriptionToken Subscribe(Action<TaskEndedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEvent.yml" sourcestartlinenumber="1">Unsubscribe from TaskEndedEvents by specifying the token that was returned by <xref href="ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEvent.Subscribe(System.Action%7bArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;TaskEndedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEvent.yml" sourcestartlinenumber="1">Unsubscribe from TaskEndedEvents by specifying the same action that was given to <xref href="ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEvent.Subscribe(System.Action%7bArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<TaskEndedEventArgs> action)
```


