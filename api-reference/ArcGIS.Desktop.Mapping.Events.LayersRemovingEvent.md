# LayersRemovingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersRemovingEvent.yml" sourcestartlinenumber="1">Occurs when a layer is about to be removed from a map giving a chance to cancel.</p>


## Object Signature

```csharp
public sealed class LayersRemovingEvent : AsyncPresentationEvent<LayersRemovingEventArgs>
```


## Members

### Subscribe(Func&lt;LayersRemovingEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersRemovingEvent.yml" sourcestartlinenumber="1">Subscribe to the LayersRemovingEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Func<LayersRemovingEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersRemovingEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;LayersRemovingEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersRemovingEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Func<LayersRemovingEventArgs, Task> action)
```


