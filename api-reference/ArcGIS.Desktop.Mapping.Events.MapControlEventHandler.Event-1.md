# MapControlEventHandler.Event&lt;TEventArgs&gt;

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.Event-1.yml" sourcestartlinenumber="1">Represents a map control input event that can be subscribed to.</p>


## Object Signature

```csharp
public sealed class MapControlEventHandler.Event<TEventArgs> where TEventArgs : MapControlEventArgs
```


## Members

### Subscribe(Action&lt;TEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.Event-1.yml" sourcestartlinenumber="1">Subscribes to the event.</p>


```csharp
public SubscriptionToken Subscribe(Action<TEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.Event-1.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;TEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.Event-1.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public void Unsubscribe(Action<TEventArgs> action)
```


