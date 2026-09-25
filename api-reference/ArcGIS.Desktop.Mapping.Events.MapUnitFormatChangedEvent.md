# MapUnitFormatChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapUnitFormatChangedEvent.yml" sourcestartlinenumber="1">Occurs when a map display unit format is changed.</p>


## Object Signature

```csharp
public sealed class MapUnitFormatChangedEvent : CompositePresentationEvent<MapUnitFormatChangedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapUnitFormatChangedEvent.yml" sourcestartlinenumber="1">Current unit format changes include the map location and elevation unit formats.<br>
Unit format changes can also occur when a map is not active or before a map is initialized in
which case the <xref href="ArcGIS.Desktop.Mapping.Events.MapUnitFormatChangedEventArgs.Map" data-throw-if-not-resolved="false"></xref> property can be null.</p>


## Members

### Subscribe(Action&lt;MapUnitFormatChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapUnitFormatChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the MapUnitFormatChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<MapUnitFormatChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapUnitFormatChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;MapUnitFormatChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapUnitFormatChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<MapUnitFormatChangedEventArgs> action)
```


