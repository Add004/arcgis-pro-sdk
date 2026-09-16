# ProProjectSavingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingEvent.yml" sourcestartlinenumber="1">Occurs when a project has been saved</p>


## Object Signature

```csharp
[Obsolete("ProProjectSavingEvent is deprecated at 3.3. It is not used")]
public sealed class ProProjectSavingEvent : CompositePresentationEvent<ProProjectEventArgs>
```


## Members

### Subscribe(Action&lt;ProProjectEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingEvent.yml" sourcestartlinenumber="1">Subscribe to the ProProjectSavingEvent</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProProjectEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProProjectSavingEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProProjectEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProProjectSavingEvent</p>


```csharp
public static void Unsubscribe(Action<ProProjectEventArgs> action)
```


