# ReportAddedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>.<a class="xref" href="ArcGIS.Desktop.Reports.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportAddedEvent.yml" sourcestartlinenumber="1">Occurs when a <xref href="ArcGIS.Desktop.Reports.Report?text=Report" data-throw-if-not-resolved="false"></xref> is added to the project.</p>


## Object Signature

```csharp
public class ReportAddedEvent : CompositePresentationEvent<ReportUpdatedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportAddedEvent.yml" sourcestartlinenumber="1">This event will be called if a report is manually inserted using the UI, copied and pasted into a project, or if a report is imported from another file.
Reference <xref href="ArcGIS.Desktop.Reports.Events.ReportUpdatedEventArgs?text=ReportUpdatedEventArgs" data-throw-if-not-resolved="false"></xref> to get a list of arguments.</p>


## Members

### Subscribe(Action&lt;ReportUpdatedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportAddedEvent.yml" sourcestartlinenumber="1">Subscribe to the ReportAddedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ReportUpdatedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportAddedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken?text=SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ReportUpdatedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportAddedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<ReportUpdatedEventArgs> action)
```


