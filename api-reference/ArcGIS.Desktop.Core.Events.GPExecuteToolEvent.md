# GPExecuteToolEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEvent.yml" sourcestartlinenumber="1">Occurs when a Geoprocessing Tool is executed</p>


## Object Signature

```csharp
public sealed class GPExecuteToolEvent : CompositePresentationEvent<GPExecuteToolEventArgs>
```


## Members

### GPExecuteToolEvent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEvent.yml" sourcestartlinenumber="1">Occurs when a Geoprocessing Tool is executed</p>


```csharp
public GPExecuteToolEvent()
```
### Subscribe(Action&lt;GPExecuteToolEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEvent.yml" sourcestartlinenumber="1">Subscribe to the GPExecuteToolEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<GPExecuteToolEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;GPExecuteToolEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list..</p>


```csharp
public static void Unsubscribe(Action<GPExecuteToolEventArgs> action)
```


