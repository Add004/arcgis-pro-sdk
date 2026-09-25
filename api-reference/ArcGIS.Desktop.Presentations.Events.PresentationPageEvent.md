# PresentationPageEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationPageEvent.yml" sourcestartlinenumber="1">Represents a presentation page event.</p>


## Object Signature

```csharp
public sealed class PresentationPageEvent : CompositePresentationEvent<PresentationPageEventArgs>
```


## Members

### Subscribe(Action&lt;PresentationPageEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationPageEvent.yml" sourcestartlinenumber="1">Subscribe to the PresentationPageEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<PresentationPageEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationPageEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;PresentationPageEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationPageEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<PresentationPageEventArgs> action)
```


