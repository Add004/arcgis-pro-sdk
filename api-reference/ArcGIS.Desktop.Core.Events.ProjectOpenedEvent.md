# ProjectOpenedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenedEvent.yml" sourcestartlinenumber="1">Occurs when a project has been opened</p>


## Object Signature

```csharp
public sealed class ProjectOpenedEvent : CompositePresentationEvent<ProjectEventArgs>
```


## Members

### Subscribe(Action&lt;ProjectEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenedEvent.yml" sourcestartlinenumber="1">Subscribe to the ProjectOpenedEvent</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProjectEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectOpenedEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProjectEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenedEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ProjectOpenedEvent</p>


```csharp
public static void Unsubscribe(Action<ProjectEventArgs> action)
```


