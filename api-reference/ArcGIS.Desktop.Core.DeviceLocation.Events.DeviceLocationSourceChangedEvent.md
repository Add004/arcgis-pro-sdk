# DeviceLocationSourceChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.html">DeviceLocation</a>.<a class="xref" href="ArcGIS.Desktop.Core.DeviceLocation.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Events.DeviceLocationSourceChangedEvent.yml" sourcestartlinenumber="1">Occurs when the local device location source is switched.</p>


## Object Signature

```csharp
public sealed class DeviceLocationSourceChangedEvent : CompositePresentationEvent<DeviceLocationSourceChangedEventArgs>
```


## Members

### Subscribe(Action&lt;DeviceLocationSourceChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Events.DeviceLocationSourceChangedEvent.yml" sourcestartlinenumber="1">Subscribes to the DeviceLocationSourceChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<DeviceLocationSourceChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Events.DeviceLocationSourceChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;DeviceLocationSourceChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.DeviceLocation.Events.DeviceLocationSourceChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<DeviceLocationSourceChangedEventArgs> action)
```


