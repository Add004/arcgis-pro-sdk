# ProjectHomeFolderChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEvent.yml" sourcestartlinenumber="1">Occurs when the home folder of the current project is changed after initialization. This event's subscribers will always be called on a worker thread.</p>


## Object Signature

```csharp
public sealed class ProjectHomeFolderChangedEvent : CompositePresentationEvent<ProjectHomeFolderChangedEventArgs>
```


## Members

### ProjectHomeFolderChangedEvent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEvent.yml" sourcestartlinenumber="1">Occurs when the home folder of the current project is changed after initialization. This event's subscribers will always be called on a worker thread.</p>


```csharp
public ProjectHomeFolderChangedEvent()
```
### Subscribe(Action&lt;ProjectHomeFolderChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the ProjectHomeFolderChangedEvent event.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProjectHomeFolderChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectHomeFolderChangedEvent event</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProjectHomeFolderChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ProjectHomeFolderChangedEvent event</p>


```csharp
public static void Unsubscribe(Action<ProjectHomeFolderChangedEventArgs> action)
```


