# MapClosedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapClosedEvent.yml" sourcestartlinenumber="1">Occurs when a map is closed.</p>


## Object Signature

```csharp
public sealed class MapClosedEvent : CompositePresentationEvent<MapClosedEventArgs>
```


## Members

### Subscribe(Action&lt;MapClosedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapClosedEvent.yml" sourcestartlinenumber="1">Subscribe to the MapClosedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<MapClosedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapClosedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;MapClosedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapClosedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<MapClosedEventArgs> action)
```


