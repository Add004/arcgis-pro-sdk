# ApplicationClosingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ApplicationClosingEvent.yml" sourcestartlinenumber="1">Occurs when the the application is attempting to shutdown and can be handled to cancel the closure.</p>


## Object Signature

```csharp
public sealed class ApplicationClosingEvent : AsyncPresentationEvent<CancelEventArgs>
```


## Members

### Subscribe(Func&lt;CancelEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ApplicationClosingEvent.yml" sourcestartlinenumber="1">Call the specified method whenever the event occurs.</p>


```csharp
public static SubscriptionToken Subscribe(Func<CancelEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ApplicationClosingEvent.yml" sourcestartlinenumber="1">Stop being notified when the event occurs.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;CancelEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ApplicationClosingEvent.yml" sourcestartlinenumber="1">Stop being notified when the event occurs.</p>


```csharp
public static void Unsubscribe(Func<CancelEventArgs, Task> action)
```


