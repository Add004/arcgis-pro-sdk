# PortalSignOnChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEventArgs.yml" sourcestartlinenumber="1">Data for the  <xref href="ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class PortalSignOnChangedEventArgs : EventArgs
```


## Members

### IsSignedOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEventArgs.yml" sourcestartlinenumber="1">Gets the signed on state of the portal triggering the event</p>


```csharp
public bool IsSignedOn { get; }
```
### Portal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEventArgs.yml" sourcestartlinenumber="1">Gets the portal whose signed on state has changed</p>


```csharp
public ArcGISPortal Portal { get; }
```


