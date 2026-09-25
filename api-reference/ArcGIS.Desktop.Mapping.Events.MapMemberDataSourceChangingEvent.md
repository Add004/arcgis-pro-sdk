# MapMemberDataSourceChangingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberDataSourceChangingEvent.yml" sourcestartlinenumber="1">Occurs when a layer or standalone table's datasource is about to change giving a chance to cancel.</p>


## Object Signature

```csharp
public sealed class MapMemberDataSourceChangingEvent : AsyncPresentationEvent<MapMemberCancelEventsArgs>
```


## Members

### MapMemberDataSourceChangingEvent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberDataSourceChangingEvent.yml" sourcestartlinenumber="1">Occurs when a layer or standalone table's datasource is about to change giving a chance to cancel.</p>


```csharp
public MapMemberDataSourceChangingEvent()
```
### Subscribe(Func&lt;MapMemberCancelEventsArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberDataSourceChangingEvent.yml" sourcestartlinenumber="1">Subscribe to the MapMemberDataSourceChangingEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Func<MapMemberCancelEventsArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberDataSourceChangingEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;MapMemberCancelEventsArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberDataSourceChangingEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Func<MapMemberCancelEventsArgs, Task> action)
```


