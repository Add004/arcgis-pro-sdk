# PortalSignOnChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent.yml" sourcestartlinenumber="1">Occurs when the sign on state of a portal changes.</p>


## Object Signature

```csharp
public sealed class PortalSignOnChangedEvent : CompositePresentationEvent<PortalSignOnChangedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent.yml" sourcestartlinenumber="1">The portal triggering the event does not have to be the active portal<br>
The portal must currently be in the list of portals -
<xref href="ArcGIS.Desktop.Core.ArcGISPortalManager.GetPortals" data-throw-if-not-resolved="false"></xref></p>


## Members

### Subscribe(Action&lt;PortalSignOnChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the PortalSignOnChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<PortalSignOnChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;PortalSignOnChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list..</p>


```csharp
public static void Unsubscribe(Action<PortalSignOnChangedEventArgs> action)
```


