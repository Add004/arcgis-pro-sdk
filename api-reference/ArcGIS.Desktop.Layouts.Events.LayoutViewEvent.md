# LayoutViewEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEvent.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Layouts.LayoutView?text=LayoutView" data-throw-if-not-resolved="false"></xref> is initialized, activated or its extent is changed.</p>


## Object Signature

```csharp
public sealed class LayoutViewEvent : CompositePresentationEvent<LayoutViewEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEvent.yml" sourcestartlinenumber="1">Reference <xref href="ArcGIS.Desktop.Layouts.Events.LayoutViewEventArgs?text=LayoutViewEventArgs" data-throw-if-not-resolved="false"></xref> to get a list of arguments.</p>


## Members

### Subscribe(Action&lt;LayoutViewEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEvent.yml" sourcestartlinenumber="1">Subscribe to the LayoutViewEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<LayoutViewEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;LayoutViewEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutViewEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<LayoutViewEventArgs> action)
```


