# ActiveParcelRecordChangingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveParcelRecordChangingEvent.yml" sourcestartlinenumber="1">Occurs when the active parcel record changes.</p>


## Object Signature

```csharp
public sealed class ActiveParcelRecordChangingEvent : CompositePresentationEvent<ParcelRecordEventArgs>
```


## Members

### Subscribe(Action&lt;ParcelRecordEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveParcelRecordChangingEvent.yml" sourcestartlinenumber="1">Subscribe to active record change event.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ParcelRecordEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveParcelRecordChangingEvent.yml" sourcestartlinenumber="1">Unsubscribe to the active record change event.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ParcelRecordEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveParcelRecordChangingEvent.yml" sourcestartlinenumber="1">Unsubscribe to the active record change event.</p>


```csharp
public static void Unsubscribe(Action<ParcelRecordEventArgs> action)
```


