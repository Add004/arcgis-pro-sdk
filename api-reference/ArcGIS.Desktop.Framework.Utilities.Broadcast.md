# Broadcast

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Utilities.html">Utilities</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.Broadcast.yml" sourcestartlinenumber="1">Class used for communicating between multiple instances of Pro using a publish/subscribe model.
Messages are organized around a uniquely named channel.  Subscribers can limit what messages they receive by subscribing to a
specific channel.  Publishers specify a channel when posting messages. Calling publish when fewer than two instances of
Pro are running will produce no messages.</p>


## Object Signature

```csharp
public static class Broadcast
```


## Members

### Publish(Guid, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.Broadcast.yml" sourcestartlinenumber="1">Broadcasts a message on the specified channel to all running instances of Pro.</p>


```csharp
public static bool Publish(Guid channel, int messageID, string message)
```
### Subscribe(Guid, Action&lt;int, string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.Broadcast.yml" sourcestartlinenumber="1">Subscribes to the channel identified by the channel argument.  The specified action will be invoked when a message is sent to this channel.</p>


```csharp
public static ulong Subscribe(Guid channel, Action<int, string> action)
```
### Unsubscribe(ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Utilities.Broadcast.yml" sourcestartlinenumber="1">Unregisters a previously registered subscription using the specified subscription id.</p>


```csharp
public static void Unsubscribe(ulong cookie)
```


