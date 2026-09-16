# TaskStartedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEvent.yml" sourcestartlinenumber="1">Occurs when execution of a task starts.</p>


## Object Signature

```csharp
public sealed class TaskStartedEvent : CompositePresentationEvent<TaskStartedEventArgs>
```


## Members

### Subscribe(Action&lt;TaskStartedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEvent.yml" sourcestartlinenumber="1">Subscribes to TaskStartedEvents that are published when a task is commenced.</p>


```csharp
public static SubscriptionToken Subscribe(Action<TaskStartedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEvent.yml" sourcestartlinenumber="1">Unsubscribe from TaskStartedEvents by specifying the token that was returned by <xref href="ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEvent.Subscribe(System.Action%7bArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;TaskStartedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEvent.yml" sourcestartlinenumber="1">Unsubscribe from TaskStartedEvents by specifying the same action that was given to <xref href="ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEvent.Subscribe(System.Action%7bArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<TaskStartedEventArgs> action)
```


