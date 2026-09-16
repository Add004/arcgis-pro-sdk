# AsyncPresentationEvent&lt;TPayload&gt;

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Events.html">Events</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Defines a class that manages publication and subscription to events.</p>


## Object Signature

```csharp
public abstract class AsyncPresentationEvent<TPayload> : EventBase
```


## Members

### BroadcastAsync(TPayload)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Publishes the <xref href="ArcGIS.Core.Events.CompositePresentationEvent%601" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Task BroadcastAsync(TPayload payload)
```
### Contains(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Returns <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if there is a subscriber matching <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool Contains(SubscriptionToken token)
```
### Contains(Func&lt;TPayload, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Returns <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if there is a subscriber matching <xref href="System.Action%601" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool Contains(Func<TPayload, Task> subscriber)
```
### ContainsAny()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Returns <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if there are currently any subscribers.</p>


```csharp
protected bool ContainsAny()
```
### OnFirstRegister()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Called when the first subscriber subscribes to this event.</p>


```csharp
protected virtual void OnFirstRegister()
```
### OnLastUnregister()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Called when the last subscriber unsubscribes from this event.</p>


```csharp
protected virtual void OnLastUnregister()
```
### Register(Func&lt;TPayload, Task&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Subscribes a delegate to an event that will be published on the publisher thread.
<xref href="ArcGIS.Core.Events.AsyncPresentationEvent%601" data-throw-if-not-resolved="false"></xref> will maintain a <xref href="System.WeakReference" data-throw-if-not-resolved="false"></xref> to the target of the supplied <code class="paramref">action</code> delegate.</p>


```csharp
public SubscriptionToken Register(Func<TPayload, Task> action, bool keepSubscriberAlive = false)
```
### Unregister(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void Unregister(SubscriptionToken token)
```
### Unregister(Func&lt;TPayload, Task&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.AsyncPresentationEvent-1.yml" sourcestartlinenumber="1">Removes the first subscriber matching <xref href="System.Action%601" data-throw-if-not-resolved="false"></xref> from the subscribers' list.</p>


```csharp
public void Unregister(Func<TPayload, Task> subscriber)
```


