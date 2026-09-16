# ProjectUnitFormatsChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEvent.yml" sourcestartlinenumber="1">Event raised when any of the project unit formats are changed, new ones added
or existing ones removed. Unit format changes are per-project</p>


## Object Signature

```csharp
public sealed class ProjectUnitFormatsChangedEvent : CompositePresentationEvent<ProjectUnitFormatsChangedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEvent.yml" sourcestartlinenumber="1">This event is only fired when there is an active project. Check the
<xref href="ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs" data-throw-if-not-resolved="false"></xref> to determine if a change of one or more
of the project default format units was made as part of the event.<br>
Note: ProjectUnitFormatsChangedEvent is also fired in response to changes made via the
Project Options UI off backstage. The <xref href="ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs.DefaultsChangedHint" data-throw-if-not-resolved="false"></xref>
will contain all <xref href="ArcGIS.Desktop.Core.UnitFormats.UnitFormatType" data-throw-if-not-resolved="false"></xref> values for an event originating from the Options
UI.</p>


## Members

### Subscribe(Action&lt;ProjectUnitFormatsChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the ProjectUnitFormatsChangedEvent event</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProjectUnitFormatsChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectUnitFormatsChangedEvent event</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProjectUnitFormatsChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProjectUnitFormatsChangedEvent event</p>


```csharp
public static void Unsubscribe(Action<ProjectUnitFormatsChangedEventArgs> action)
```


