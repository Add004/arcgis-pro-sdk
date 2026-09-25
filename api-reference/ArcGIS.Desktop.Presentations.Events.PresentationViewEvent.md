# PresentationViewEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationViewEvent.yml" sourcestartlinenumber="1">Represents a presentation view event.</p>


## Object Signature

```csharp
public sealed class PresentationViewEvent : CompositePresentationEvent<PresentationViewEventArgs>
```


## Members

### Subscribe(Action&lt;PresentationViewEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationViewEvent.yml" sourcestartlinenumber="1">Subscribe to the PresentationViewEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<PresentationViewEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationViewEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;PresentationViewEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Events.PresentationViewEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<PresentationViewEventArgs> action)
```


