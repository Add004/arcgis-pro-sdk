# ProjectWindowSelectedItemsChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent.yml" sourcestartlinenumber="1">Occurs when the selection changes in either the Project dockpane (&quot;Catalog pane&quot;) or any
Project pane instance (&quot;Catalog view&quot;).</p>


## Object Signature

```csharp
public sealed class ProjectWindowSelectedItemsChangedEvent : CompositePresentationEvent<ProjectWindowSelectedItemsChangedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent.yml" sourcestartlinenumber="1">The project window that triggered the selection change can be accessed via the
<xref href="ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs" data-throw-if-not-resolved="false"></xref> passed to your event subscriber's action.</p>


## Members

### Subscribe(Action&lt;ProjectWindowSelectedItemsChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the ProjectWindowSelectedItemsChangedEvent</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProjectWindowSelectedItemsChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectWindowSelectedItemsChangedEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProjectWindowSelectedItemsChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe the delegate from the ProjectWindowSelectedItemsChangedEvent</p>


```csharp
public static void Unsubscribe(Action<ProjectWindowSelectedItemsChangedEventArgs> action)
```


