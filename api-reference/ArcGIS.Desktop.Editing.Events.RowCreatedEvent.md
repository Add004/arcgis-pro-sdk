# RowCreatedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowCreatedEvent.yml" sourcestartlinenumber="1">Occurs when a Row is created.</p>


## Object Signature

```csharp
public static class RowCreatedEvent
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowCreatedEvent.yml" sourcestartlinenumber="1">The RowCreatedEvent is published <b><i>during</i></b> the execution of the edit operation.  Any modifications performed within the RowEvent handler can cause cascaded events to
be generated.  Make sure you have an exit condition to avoid infinite recursion.   For example, if you are changing a feature attribute within a RowCreatedEvent or RowChangedEvent,
consider tracking that feature's objectID to ignore the corresponding RowChangedEvent your attribute change will generate.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowCreatedEvent.yml" sourcestartlinenumber="7">If you need to edit additional tables within the RowEvent you MUST use the ArcGIS.Core.Data API to edit the tables directly.  Do NOT use a new edit operation to create
or modify features or rows in your RowEvent callback.</p>


## Members

### Subscribe(Action&lt;RowChangedEventArgs&gt;, Table, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowCreatedEvent.yml" sourcestartlinenumber="1">Subscribes to RowCreatedEvents that are published when a row is created. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SubscriptionToken Subscribe(Action<RowChangedEventArgs> action, Table table, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowCreatedEvent.yml" sourcestartlinenumber="1">Unsubscribe from RowCreatedEvents. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```


