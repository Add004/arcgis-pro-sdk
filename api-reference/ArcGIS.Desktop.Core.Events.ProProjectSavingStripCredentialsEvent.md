# ProProjectSavingStripCredentialsEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingStripCredentialsEvent.yml" sourcestartlinenumber="1">Occurs when a project has been saved with strip credentials attribute set to true
This event gives the opportunity to strip credentials from anything that the subscriber
may be persisting in the project. It's important to note that the projectID that is passed
is not the projectID of the currently open project. It is the projectID of the project that
is being opened in the background specifically for the purpose of stripping credentials.</p>


## Object Signature

```csharp
public sealed class ProProjectSavingStripCredentialsEvent : CompositePresentationEvent<ProProjectStripCredentialsEventArgs>
```


## Members

### Subscribe(Action&lt;ProProjectStripCredentialsEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingStripCredentialsEvent.yml" sourcestartlinenumber="1">Subscribe to the ProProjectSavingStripCredentialsEvent</p>


```csharp
public static SubscriptionToken Subscribe(Action<ProProjectStripCredentialsEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingStripCredentialsEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProProjectSavingStripCredentialsEvent</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;ProProjectStripCredentialsEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingStripCredentialsEvent.yml" sourcestartlinenumber="1">Unsubscribe from the ProProjectSavingStripCredentialsEvent</p>


```csharp
public static void Unsubscribe(Action<ProProjectStripCredentialsEventArgs> action)
```


