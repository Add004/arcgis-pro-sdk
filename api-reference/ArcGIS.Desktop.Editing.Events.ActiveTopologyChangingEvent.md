# ActiveTopologyChangingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTopologyChangingEvent.yml" sourcestartlinenumber="1">Occurs when the active topology changes</p>


## Object Signature

```csharp
public sealed class ActiveTopologyChangingEvent : CompositePresentationEvent<TopologyEventArgs>
```


## Members

### Subscribe(Action&lt;TopologyEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTopologyChangingEvent.yml" sourcestartlinenumber="1">Subscribe to topology option change event.</p>


```csharp
public static SubscriptionToken Subscribe(Action<TopologyEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTopologyChangingEvent.yml" sourcestartlinenumber="1">Unubscribe to topology option change event.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;TopologyEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTopologyChangingEvent.yml" sourcestartlinenumber="1">Unubscribe to topology option change event.</p>


```csharp
public static void Unsubscribe(Action<TopologyEventArgs> action)
```


