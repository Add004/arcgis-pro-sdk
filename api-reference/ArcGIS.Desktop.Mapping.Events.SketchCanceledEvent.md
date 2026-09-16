# SketchCanceledEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">Occurs when a sketch is canceled.</p>


## Object Signature

```csharp
public sealed class SketchCanceledEvent : CompositePresentationEvent<SketchCanceledEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">You can <xref href="ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.Subscribe(System.Action%7bArcGIS.Desktop.Mapping.Events.SketchCanceledEventArgs%7d%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> to listen for the SketchCanceledEvent and specify a delegate that will be executed upon
receiving the event. To stop listening, you can <see cref="O:ArcGIS.Desktop.Editing.Events.SketchCanceledEvent.Unsubscribe">Unsubscribe</see>.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="6">The following are examples of tools that publish the sketch events - construction tools, Edit Vertices, Align Features, Reshape.</p>


## Members

### OnFirstRegister()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">Called when the first subscriber subscribes to this event.</p>


```csharp
protected override void OnFirstRegister()
```
### OnLastUnregister()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">Called when the last subscriber unsubscribes from this event.</p>


```csharp
protected override void OnLastUnregister()
```
### Subscribe(Action&lt;SketchCanceledEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">Subscribes to the SketchCanceledEvent that is published when a sketch is canceled within certain tools.</p>


```csharp
public static SubscriptionToken Subscribe(Action<SketchCanceledEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">Unsubscribe from the SketchCanceledEvent by specifying the token that was returned by <xref href="ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.Subscribe(System.Action%7bArcGIS.Desktop.Mapping.Events.SketchCanceledEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;SketchCanceledEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.yml" sourcestartlinenumber="1">Unsubscribe from the SketchCanceledEvent by specifying the same action that was given to <xref href="ArcGIS.Desktop.Mapping.Events.SketchCanceledEvent.Subscribe(System.Action%7bArcGIS.Desktop.Mapping.Events.SketchCanceledEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<SketchCanceledEventArgs> action)
```


