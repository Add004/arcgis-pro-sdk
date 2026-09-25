# JobMessageEventArgs&lt;T&gt;

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEventArgs-1.yml" sourcestartlinenumber="1">Job message event arguments.</p>


## Object Signature

```csharp
public class JobMessageEventArgs<T> : EventArgs where T : JobMessage
```


## Members

### JobMessageEventArgs()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEventArgs-1.yml" sourcestartlinenumber="1">Job message event arguments.</p>


```csharp
public JobMessageEventArgs()
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEventArgs-1.yml" sourcestartlinenumber="1">The event message.</p>


```csharp
public T Message { get; }
```
### MessageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEventArgs-1.yml" sourcestartlinenumber="1">The message type.</p>


```csharp
public MessageType MessageType { get; }
```
### Timestamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Events.JobMessageEventArgs-1.yml" sourcestartlinenumber="1">Timestamp of when message event occured.</p>


```csharp
public long Timestamp { get; }
```


