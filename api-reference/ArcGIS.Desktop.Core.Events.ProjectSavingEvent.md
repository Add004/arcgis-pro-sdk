# ProjectSavingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectSavingEvent.yml" sourcestartlinenumber="1">Occurs when a project in the process of being saved</p>


## Object Signature

```csharp
public sealed class ProjectSavingEvent : AsyncPresentationEvent<ProjectEventArgs>
```


## Members

### Subscribe(Func&lt;ProjectEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectSavingEvent.yml" sourcestartlinenumber="1">Subscribe to the ProjectSavingEvent</p>


```csharp
public static SubscriptionToken Subscribe(Func<ProjectEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectSavingEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectSavingEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;ProjectEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectSavingEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ProjectSavingEvent</p>


```csharp
public static void Unsubscribe(Func<ProjectEventArgs, Task> action)
```


