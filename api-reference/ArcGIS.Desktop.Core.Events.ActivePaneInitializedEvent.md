# ActivePaneInitializedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEvent.yml" sourcestartlinenumber="1">Occurs when a the active pane is fully initialized</p>


## Object Signature

```csharp
public sealed class ActivePaneInitializedEvent : CompositePresentationEvent<ActivePaneInitializedEventArgs>
```


## Members

### Publish(ActivePaneInitializedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEvent.yml" sourcestartlinenumber="1">Rebroadcast the ActivePaneInitializedEvent</p>


```csharp
public static void Publish(ActivePaneInitializedEventArgs activePaneInitializedEventArgs)
```
### Subscribe(Action&lt;ActivePaneInitializedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEvent.yml" sourcestartlinenumber="1">Subscribes to the ActivePaneInitializedEvent</p>


```csharp
public static SubscriptionToken Subscribe(Action<ActivePaneInitializedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ActivePaneInitializedEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ActivePaneInitializedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ActivePaneInitializedEvent</p>


```csharp
public static void Unsubscribe(Action<ActivePaneInitializedEventArgs> action)
```


