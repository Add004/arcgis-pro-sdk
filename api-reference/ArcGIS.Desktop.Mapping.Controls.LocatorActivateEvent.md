# LocatorActivateEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="1">For use by third party developers when using the <xref href="ArcGIS.Desktop.Mapping.Controls.LocatorControl" data-throw-if-not-resolved="false"></xref> in a custom dockpane in an add-in.</p>


## Object Signature

```csharp
public sealed class LocatorActivateEvent : CompositePresentationEvent<LocatorActivateEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="1">Override the OnActivate method of your custom dockpane and publish this event to signal to the LocatorControl that it should mark itself
as the active LocatorControl or not.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="6">See the Geocode sample in the<a href="https://github.com/esri/arcgis-pro-sdk-community-samples/tree/master/Map-Authoring" target="_blank"> ArcGIS Pro SDK community samples</a>.</p>


## Members

### Publish(LocatorActivateEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="1">Broadcast the LocatorActivateEvent</p>


```csharp
public static void Publish(LocatorActivateEventArgs eventArgs)
```
### Subscribe(Action&lt;LocatorActivateEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="1">Subscribe to the LocatorActivateEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<LocatorActivateEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;LocatorActivateEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorActivateEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<LocatorActivateEventArgs> action)
```


