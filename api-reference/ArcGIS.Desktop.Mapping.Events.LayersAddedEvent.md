# LayersAddedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersAddedEvent.yml" sourcestartlinenumber="1">Occurs when a layer is added to a map.</p>


## Object Signature

```csharp
public sealed class LayersAddedEvent : CompositePresentationEvent<LayerEventsArgs>
```


## Members

### Subscribe(Action&lt;LayerEventsArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersAddedEvent.yml" sourcestartlinenumber="1">Subscribe to the LayersAddedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<LayerEventsArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersAddedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;LayerEventsArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.LayersAddedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<LayerEventsArgs> action)
```


