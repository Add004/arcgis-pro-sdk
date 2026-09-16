# ArcGISPortalRemovedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent.yml" sourcestartlinenumber="1">Occurs when a portal is removed from the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class ArcGISPortalRemovedEvent : CompositePresentationEvent<ArcGISPortalRemovedEventArgs>
```


## Members

### Subscribe(Action&lt;ArcGISPortalRemovedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent.yml" sourcestartlinenumber="1">Subscribe to the ArcGISPortalRemovedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ArcGISPortalRemovedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ArcGISPortalRemovedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list..</p>


```csharp
public static void Unsubscribe(Action<ArcGISPortalRemovedEventArgs> action)
```


