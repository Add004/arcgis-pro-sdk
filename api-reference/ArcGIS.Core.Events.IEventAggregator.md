# IEventAggregator

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Events.html">Events</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Events.IEventAggregator.yml" sourcestartlinenumber="1">Defines an interface to get instances of an event type.</p>


## Object Signature

```csharp
public interface IEventAggregator
```


## Members

### GetEvent&lt;TEventType&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Events.IEventAggregator.yml" sourcestartlinenumber="1">Gets an instance of an event type.</p>


```csharp
TEventType GetEvent<TEventType>() where TEventType : EventBase
```


