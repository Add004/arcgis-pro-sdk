# ProjectClosingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEvent.yml" sourcestartlinenumber="1">Occurs when a project is in the process of closing</p>


## Object Signature

```csharp
public sealed class ProjectClosingEvent : AsyncPresentationEvent<ProjectClosingEventArgs>
```


## Members

### Subscribe(Func&lt;ProjectClosingEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEvent.yml" sourcestartlinenumber="1">Subscribes to the ProjectClosingEvent</p>


```csharp
public static SubscriptionToken Subscribe(Func<ProjectClosingEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectClosingEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;ProjectClosingEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ProjectClosingEvent</p>


```csharp
public static void Unsubscribe(Func<ProjectClosingEventArgs, Task> action)
```


