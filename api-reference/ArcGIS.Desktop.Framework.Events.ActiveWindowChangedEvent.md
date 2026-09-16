# ActiveWindowChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActiveWindowChangedEvent.yml" sourcestartlinenumber="1">Occurs when the active window changes. This can be a Pane or a Dockpane.</p>


## Object Signature

```csharp
public sealed class ActiveWindowChangedEvent : CompositePresentationEvent<WindowEventArgs>
```


## Members

### Subscribe(Action&lt;WindowEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActiveWindowChangedEvent.yml" sourcestartlinenumber="1">Call the specified method whenever the event occurs.</p>


```csharp
public static SubscriptionToken Subscribe(Action<WindowEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActiveWindowChangedEvent.yml" sourcestartlinenumber="1">Stop being notified when the event occurs.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;WindowEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ActiveWindowChangedEvent.yml" sourcestartlinenumber="1">Stop being notified when the event occurs.</p>


```csharp
public static void Unsubscribe(Action<WindowEventArgs> action)
```


