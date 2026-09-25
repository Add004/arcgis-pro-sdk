# MapRemovingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapRemovingEvent.yml" sourcestartlinenumber="1">Occurs when a map is about to be removed giving a chance to cancel.</p>


## Object Signature

```csharp
public sealed class MapRemovingEvent : AsyncPresentationEvent<MapRemovingEventArgs>
```


## Members

### Subscribe(Func&lt;MapRemovingEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapRemovingEvent.yml" sourcestartlinenumber="1">Subscribe to the MapRemovingEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Func<MapRemovingEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapRemovingEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;MapRemovingEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapRemovingEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Func<MapRemovingEventArgs, Task> action)
```


