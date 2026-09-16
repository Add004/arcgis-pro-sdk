# EditStartedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEvent.yml" sourcestartlinenumber="1">Occurs when an ArcGIS.Desktop.Editing.EditOperation begins executing.</p>


## Object Signature

```csharp
public sealed class EditStartedEvent : CompositePresentationEvent<EditStartedEventArgs>
```


## Members

### Subscribe(Action&lt;EditStartedEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEvent.yml" sourcestartlinenumber="1">Subscribes to EditStartedEvent that are published when an <xref href="ArcGIS.Desktop.Editing.EditOperation" data-throw-if-not-resolved="false"></xref> is executed.</p>


```csharp
public static SubscriptionToken Subscribe(Action<EditStartedEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEvent.yml" sourcestartlinenumber="1">Unsubscribe from EditStartedEvent by specifying the token that was returned by <xref href="ArcGIS.Desktop.Editing.Events.EditStartedEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.EditStartedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;EditStartedEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEvent.yml" sourcestartlinenumber="1">Unsubscribe from EditStartedEvent by specifying the same action that was given to <xref href="ArcGIS.Desktop.Editing.Events.EditStartedEvent.Subscribe(System.Action%7bArcGIS.Desktop.Editing.Events.EditStartedEventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<EditStartedEventArgs> action)
```


