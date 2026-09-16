# ElevationCapturingEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.yml" sourcestartlinenumber="1">Occurs when an <xref href="ArcGIS.Desktop.Editing.ElevationCapturing?text=ElevationCapturing" data-throw-if-not-resolved="false"></xref> property has changed.</p>


## Object Signature

```csharp
public sealed class ElevationCapturingEvent : AsyncPresentationEvent<ElevationCapturingEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.yml" sourcestartlinenumber="1">You can <xref href="ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.Subscribe(System.Func%7bArcGIS.Desktop.Editing.Events.ElevationCapturingEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref> to listen for ElevationCapturingEvents and specify a delegate that will be executed upon receiving the event. To
stop listening, you can <see cref="O:ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.Unsubscribe">Unsubscribe</see>.
<xref href="ArcGIS.Desktop.Editing.Events.ElevationCapturingEventArgs?text=ElevationCapturingEventArgs" data-throw-if-not-resolved="false"></xref> holds information about the event.</p>


## Members

### Subscribe(Func&lt;ElevationCapturingEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.yml" sourcestartlinenumber="1">Subscribes to ElevationCapturingEvents that are published when an <xref href="ArcGIS.Desktop.Editing.ElevationCapturing?text=ElevationCapturing" data-throw-if-not-resolved="false"></xref> property has changed.</p>


```csharp
public static SubscriptionToken Subscribe(Func<ElevationCapturingEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.yml" sourcestartlinenumber="1">Unsubscribe from ElevationCapturingEvents by specifying the token that was returned by <xref href="ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.Subscribe(System.Func%7bArcGIS.Desktop.Editing.Events.ElevationCapturingEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;ElevationCapturingEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.yml" sourcestartlinenumber="1">Unsubscribe from ElevationCapturingEvents by specifying the same action that was given to <xref href="ArcGIS.Desktop.Editing.Events.ElevationCapturingEvent.Subscribe(System.Func%7bArcGIS.Desktop.Editing.Events.ElevationCapturingEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Func<ElevationCapturingEventArgs, Task> action)
```


