# ElementEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEvent.yml" sourcestartlinenumber="1">Occurs when an <xref href="ArcGIS.Desktop.Layouts.Element?text=Element" data-throw-if-not-resolved="false"></xref> style is changed.</p>


## Object Signature

```csharp
public class ElementEvent : CompositePresentationEvent<ElementEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEvent.yml" sourcestartlinenumber="1">This event is specific to changes to an element's style. For listening to general changes to the element's properties,
use <xref href="ArcGIS.Desktop.Layouts.Events.ElementEvent?text=+ElementsUpdatedEvent" data-throw-if-not-resolved="false"></xref> instead.
Reference <xref href="ArcGIS.Desktop.Layouts.Events.ElementEventArgs?text=ElementEventArgs" data-throw-if-not-resolved="false"></xref> to get a list of arguments.</p>


## Members

### Subscribe(Action&lt;ElementEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEvent.yml" sourcestartlinenumber="1">Subscribe to the ElementEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ElementEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ElementEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<ElementEventArgs> action)
```


