# LayoutEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEvent.yml" sourcestartlinenumber="1">Occurs when the active <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref> is changed.</p>


## Object Signature

```csharp
public class LayoutEvent : CompositePresentationEvent<LayoutEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEvent.yml" sourcestartlinenumber="1">Reference <xref href="ArcGIS.Desktop.Layouts.Events.LayoutEventArgs?text=LayoutEventArgs" data-throw-if-not-resolved="false"></xref> to get a list of arguments.</p>


## Members

### Subscribe(Action&lt;LayoutEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEvent.yml" sourcestartlinenumber="1">Subscribe to the LayoutEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<LayoutEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken?text=SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;LayoutEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.LayoutEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<LayoutEventArgs> action)
```


