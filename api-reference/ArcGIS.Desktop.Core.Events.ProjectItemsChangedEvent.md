# ProjectItemsChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEvent.yml" sourcestartlinenumber="1">Occurs when a project item is added or removed</p>


## Object Signature

```csharp
public sealed class ProjectItemsChangedEvent : CompositePresentationEvent<ProjectItemsChangedEventArgs>
```


## Members

### Subscribe(Action&lt;ProjectItemsChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEvent.yml" sourcestartlinenumber="1">Subscribes to the ProjectItemsChangedEvent</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProjectItemsChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectItemsChangedEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProjectItemsChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ProjectItemsChangedEvent</p>


```csharp
public static void Unsubscribe(Action<ProjectItemsChangedEventArgs> action)
```


