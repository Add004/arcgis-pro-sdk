# ArcGISPortalAddedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent.yml" sourcestartlinenumber="1">Occurs when the a portal is added to the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class ArcGISPortalAddedEvent : CompositePresentationEvent<ArcGISPortalAddedEventArgs>
```


## Members

### Subscribe(Action&lt;ArcGISPortalAddedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent.yml" sourcestartlinenumber="1">Subscribe to the ArcGISPortalAddedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ArcGISPortalAddedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ArcGISPortalAddedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list..</p>


```csharp
public static void Unsubscribe(Action<ArcGISPortalAddedEventArgs> action)
```


