# ActivePaneChangingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActivePaneChangingEvent.yml" sourcestartlinenumber="1">Occurs when the active pane changes. This event fires before the application changes the current application state and current tool.</p>


## Object Signature

```csharp
public sealed class ActivePaneChangingEvent : CompositePresentationEvent<PaneEventArgs>
```


## Members

### Subscribe(Action&lt;PaneEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActivePaneChangingEvent.yml" sourcestartlinenumber="1">Call the specified method whenever the event occurs.</p>


```csharp
public static SubscriptionToken Subscribe(Action<PaneEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActivePaneChangingEvent.yml" sourcestartlinenumber="1">Stop being notified when the event occurs.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;PaneEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActivePaneChangingEvent.yml" sourcestartlinenumber="1">Stop being notified when the event occurs.</p>


```csharp
public static void Unsubscribe(Action<PaneEventArgs> action)
```


