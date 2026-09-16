# EditCompletingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEvent.yml" sourcestartlinenumber="1">Occurs just before an ArcGIS.Desktop.Editing.EditOperation has completed execution.</p>


## Object Signature

```csharp
public sealed class EditCompletingEvent : CompositePresentationEvent<EditCompletingEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEvent.yml" sourcestartlinenumber="1">The event is fired just before the EditOperation.Execute state is returned.</p>


## Members

### Subscribe(Action&lt;EditCompletingEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEvent.yml" sourcestartlinenumber="1">Subscribes to EditCompletingEvent that are published when an <xref href="ArcGIS.Desktop.Editing.EditOperation" data-throw-if-not-resolved="false"></xref> is executing.</p>


```csharp
public static SubscriptionToken Subscribe(Action<EditCompletingEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEvent.yml" sourcestartlinenumber="1">Unsubscribe from EditCompletingEvent by specifying the token that was returned by <xref href="ArcGIS.Desktop.Editing.Events.EditCompletingEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.EditCompletingEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;EditCompletingEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEvent.yml" sourcestartlinenumber="1">Unsubscribe from EditCompletingEvent by specifying the same action that was given to <xref href="ArcGIS.Desktop.Editing.Events.EditCompletingEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.EditCompletingEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<EditCompletingEventArgs> action)
```


