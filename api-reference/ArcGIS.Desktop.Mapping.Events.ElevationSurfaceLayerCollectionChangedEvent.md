# ElevationSurfaceLayerCollectionChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ElevationSurfaceLayerCollectionChangedEvent.yml" sourcestartlinenumber="1">Occurs when the elevation surface layers of a map changed.</p>


## Object Signature

```csharp
public sealed class ElevationSurfaceLayerCollectionChangedEvent : CompositePresentationEvent<ElevationSurfaceLayerCollectionChangedEventArgs>
```


## Members

### ElevationSurfaceLayerCollectionChangedEvent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ElevationSurfaceLayerCollectionChangedEvent.yml" sourcestartlinenumber="1">Occurs when the elevation surface layers of a map changed.</p>


```csharp
public ElevationSurfaceLayerCollectionChangedEvent()
```
### Subscribe(Action&lt;ElevationSurfaceLayerCollectionChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ElevationSurfaceLayerCollectionChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the ElevationSurfaceLayerCollectionChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ElevationSurfaceLayerCollectionChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ElevationSurfaceLayerCollectionChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ElevationSurfaceLayerCollectionChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ElevationSurfaceLayerCollectionChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<ElevationSurfaceLayerCollectionChangedEventArgs> action)
```


