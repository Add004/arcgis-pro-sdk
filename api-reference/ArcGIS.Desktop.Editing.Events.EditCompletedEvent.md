# EditCompletedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEvent.yml" sourcestartlinenumber="1">Occurs when an <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref> completes successfully.</p>


## Object Signature

```csharp
public sealed class EditCompletedEvent : AsyncPresentationEvent<EditCompletedEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEvent.yml" sourcestartlinenumber="1">You can <xref href="ArcGIS.Desktop.Editing.Events.EditCompletedEvent.Subscribe(System.Func%7bArcGIS.Desktop.Editing.Events.EditCompletedEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref> to listen for EditCompletedEvents and specify a delegate that will be executed upon receiving the event. To
stop listening, you can <see cref="O:ArcGIS.Desktop.Editing.Events.EditCompletedEvent.Unsubscribe">Unsubscribe</see>.
<xref href="ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs?text=EventCompletedEventArgs" data-throw-if-not-resolved="false"></xref> holds information about the event.</p>


## Members

### Subscribe(Func&lt;EditCompletedEventArgs, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEvent.yml" sourcestartlinenumber="1">Subscribes to EditCompletedEvents that are published when an <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref> completes successfully.</p>


```csharp
public static SubscriptionToken Subscribe(Func<EditCompletedEventArgs, Task> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEvent.yml" sourcestartlinenumber="1">Unsubscribe from EditCompletedEvents by specifying the token that was returned by <xref href="ArcGIS.Desktop.Editing.Events.EditCompletedEvent.Subscribe(System.Func%7bArcGIS.Desktop.Editing.Events.EditCompletedEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Func&lt;EditCompletedEventArgs, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEvent.yml" sourcestartlinenumber="1">Unsubscribe from EditCompletedEvents by specifying the same action that was given to <xref href="ArcGIS.Desktop.Editing.Events.EditCompletedEvent.Subscribe(System.Func%7bArcGIS.Desktop.Editing.Events.EditCompletedEventArgs%2cSystem.Threading.Tasks.Task%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Func<EditCompletedEventArgs, Task> action)
```


