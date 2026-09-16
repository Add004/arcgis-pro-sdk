# FavoritesChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.yml" sourcestartlinenumber="1">Provides information when the favorites collection is changed.</p>


## Object Signature

```csharp
public sealed class FavoritesChangedEvent : CompositePresentationEvent<EventArgs>
```


## Members

### Subscribe(Action&lt;EventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.yml" sourcestartlinenumber="1">Subscribes to the FavoritesChangedEvent that is published when favorites are changed.</p>


```csharp
public static SubscriptionToken Subscribe(Action<EventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the FavoritesChangedEvent by specifying the token that was returned by <xref href="ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.Subscribe(System.Action%7bSystem.EventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;EventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.yml" sourcestartlinenumber="1">Unsubscribe from the FavoritesChangedEvent by specifying the same action that was given to <xref href="ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.Subscribe(System.Action%7bSystem.EventArgs%7d%2cSystem.Boolean)?text=Subscribe" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(Action<EventArgs> action)
```


