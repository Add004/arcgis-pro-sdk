# ReportSectionChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>.<a class="xref" href="ArcGIS.Desktop.Reports.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEvent.yml" sourcestartlinenumber="1">Occurs when different types of sections are added, removed, or reordered in the <xref href="ArcGIS.Desktop.Reports.Report?text=Report" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class ReportSectionChangedEvent : CompositePresentationEvent<ReportSectionChangedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEvent.yml" sourcestartlinenumber="1">Reference <xref href="ArcGIS.Desktop.Reports.Events.ReportSectionChangedEventArgs?text=ReportSectionChangedEventArgs" data-throw-if-not-resolved="false"></xref> to get a list of arguments.</p>


## Members

### Subscribe(Action&lt;ReportSectionChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the ReportSectionChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ReportSectionChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken?text=SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ReportSectionChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<ReportSectionChangedEventArgs> action)
```


