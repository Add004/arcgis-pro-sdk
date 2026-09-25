# ProjectItemRemovingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent.yml" sourcestartlinenumber="1">Occurs before a project item is removed. It provides the opportunity to cancel.</p>


## Object Signature

```csharp
public class ProjectItemRemovingEvent : AsyncPresentationEvent<ProjectItemRemovingEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent.yml" sourcestartlinenumber="1">Reference <xref href="ArcGIS.Desktop.Core.Events.ProjectItemRemovingEventArgs?text=ProjectItemRemovingEventArgs" data-throw-if-not-resolved="false"></xref> to get a list of arguments.</p>


## Members

### Subscribe(Func&lt;ProjectItemRemovingEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent.yml" sourcestartlinenumber="1">Subscribe to the ProjectItemRemovingEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Func<ProjectItemRemovingEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken?text=SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;ProjectItemRemovingEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Func<ProjectItemRemovingEventArgs, Task> action)
```


