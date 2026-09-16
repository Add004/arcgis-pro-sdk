# PresentationEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationEvent.yml" sourcestartlinenumber="1">Represents a presentation event.</p>


## Object Signature

```csharp
public sealed class PresentationEvent : CompositePresentationEvent<PresentationEventArgs>
```


## Members

### Subscribe(Action&lt;PresentationEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationEvent.yml" sourcestartlinenumber="1">Subscribe to the PresentationEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<PresentationEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;PresentationEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<PresentationEventArgs> action)
```


