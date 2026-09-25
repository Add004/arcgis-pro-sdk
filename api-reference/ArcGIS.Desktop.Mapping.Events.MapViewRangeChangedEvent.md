# MapViewRangeChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEvent.yml" sourcestartlinenumber="1">Occurs when the range has changed in the map view.</p>


## Object Signature

```csharp
public sealed class MapViewRangeChangedEvent : CompositePresentationEvent<MapViewRangeChangedEventArgs>
```


## Members

### Subscribe(Action&lt;MapViewRangeChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the MapViewRangeChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<MapViewRangeChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;MapViewRangeChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<MapViewRangeChangedEventArgs> action)
```


