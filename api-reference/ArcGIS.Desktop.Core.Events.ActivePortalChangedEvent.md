# ActivePortalChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent.yml" sourcestartlinenumber="1">Occurs when the active portal is changed on the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class ActivePortalChangedEvent : CompositePresentationEvent<ActivePortalChangedEventArgs>
```


## Members

### Subscribe(Action&lt;ActivePortalChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the ActivePortalChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ActivePortalChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ActivePortalChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list..</p>


```csharp
public static void Unsubscribe(Action<ActivePortalChangedEventArgs> action)
```


