# BeforeSketchCompletedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">Occurs before a sketch is completed.</p>


## Object Signature

```csharp
public sealed class BeforeSketchCompletedEvent : AsyncPresentationEvent<BeforeSketchCompletedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">You can <xref href="ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.Subscribe(System.Func%7bArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> to listen for the BeforeSketchCompletedEvent and specify a delegate that will be executed upon
receiving the event. To stop listening, you can <see cref="O:ArcGIS.Desktop.Editing.Events.BeforeSketchCompletedEvent.Unsubscribe">Unsubscribe</see>.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="6">The following are examples of tools that publish the sketch events - construction tools, Edit Vertices, Align Features, Reshape.</p>
<p></p><p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="10">The BeforeSketchCompletedEvent fires when a sketch is finished but before the SketchCompletedEvent and MapTool.OnSketchCompleteAsync.
This event can be used to read the current sketch geometry and update it via the BeforeSketchCompletedEventArgs.SetSketchGeometry method.
If there are multiple listeners to the event, each gets the latest modified sketch geometry from the previous listener.</p>


## Members

### OnFirstRegister()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">Called when the first subscriber subscribes to this event.</p>


```csharp
protected override void OnFirstRegister()
```
### OnLastUnregister()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">Called when the last subscriber unsubscribes from this event.</p>


```csharp
protected override void OnLastUnregister()
```
### Subscribe(Func&lt;BeforeSketchCompletedEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">Subscribes to the BeforeSketchCompletedEvent that is published before a sketch is completed within certain tools.</p>


```csharp
public static SubscriptionToken Subscribe(Func<BeforeSketchCompletedEventArgs, Task> func, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the BeforeSketchCompletedEvent by specifying the token that was returned by <xref href="ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.Subscribe(System.Func%7bArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;BeforeSketchCompletedEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the BeforeSketchCompletedEvent by specifying the same action that was given to <xref href="ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEvent.Subscribe(System.Func%7bArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Func<BeforeSketchCompletedEventArgs, Task> func)
```


