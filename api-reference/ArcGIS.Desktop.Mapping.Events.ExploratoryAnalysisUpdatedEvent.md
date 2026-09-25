# ExploratoryAnalysisUpdatedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ExploratoryAnalysisUpdatedEvent.yml" sourcestartlinenumber="1">Event to notify whenever an exploratory analysis object has changed.</p>


## Object Signature

```csharp
public sealed class ExploratoryAnalysisUpdatedEvent : CompositePresentationEvent<ExploratoryAnalysisUpdatedEventArgs>
```


## Members

### Subscribe(Action&lt;ExploratoryAnalysisUpdatedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ExploratoryAnalysisUpdatedEvent.yml" sourcestartlinenumber="1">Subscribe an action to this event.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ExploratoryAnalysisUpdatedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ExploratoryAnalysisUpdatedEvent.yml" sourcestartlinenumber="1">Unsubscribe from this event.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ExploratoryAnalysisUpdatedEventArgs&gt;)

- Kind: method


```csharp
public static void Unsubscribe(Action<ExploratoryAnalysisUpdatedEventArgs> action)
```


