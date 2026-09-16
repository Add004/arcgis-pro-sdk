# GroundToGridEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEvent.yml" sourcestartlinenumber="1">Events that are published by <xref href="ArcGIS.Desktop.Editing.GroundToGridCorrection" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class GroundToGridEvent : CompositePresentationEvent<GroundToGridEventArgs>
```


## Members

### Subscribe(Action&lt;GroundToGridEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEvent.yml" sourcestartlinenumber="1">Subscribes to GroundToGridEvents that are published when a <xref href="ArcGIS.Desktop.Editing.GroundToGridCorrection" data-throw-if-not-resolved="false"></xref> property has changed.</p>


```csharp
public static SubscriptionToken Subscribe(Action<GroundToGridEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEvent.yml" sourcestartlinenumber="1">Unsubscribe from GroundToGridEvents by specifying the same action that was given to Subscribe.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;GroundToGridEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEvent.yml" sourcestartlinenumber="1">Unsubscribe from GroundToGridEvents by specifying the token that was returned by Subscribe.</p>


```csharp
public static void Unsubscribe(Action<GroundToGridEventArgs> action)
```


