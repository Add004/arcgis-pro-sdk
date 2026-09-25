# ActiveTemplateChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">Occurs when the active template is changed.</p>


## Object Signature

```csharp
public sealed class ActiveTemplateChangedEvent : CompositePresentationEvent<ActiveTemplateChangedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">You can <xref href="ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs%7d%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> to listen for the ActiveTemplateChangedEvent and specify a delegate that will be executed upon
receiving the event. To stop listening, you can <see cref="O:ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.Unsubscribe">Unsubscribe</see>.</p>


## Members

### OnFirstRegister()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">Called when the first subscriber subscribes to this event.</p>


```csharp
protected override void OnFirstRegister()
```
### OnLastUnregister()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">Called when the last subscriber unsubscribes from this event.</p>


```csharp
protected override void OnLastUnregister()
```
### Subscribe(Action&lt;ActiveTemplateChangedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">Subscribes to the ActiveTemplateChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<ActiveTemplateChangedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ActiveTemplateChangedEvent by specifying the token that was returned by <xref href="ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ActiveTemplateChangedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ActiveTemplateChangedEvent by specifying the same action that was given to <xref href="ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<ActiveTemplateChangedEventArgs> action)
```


