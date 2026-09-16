# ActiveTemplateChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs.yml" sourcestartlinenumber="1">Provides information when the active template is changed.</p>


## Object Signature

```csharp
public sealed class ActiveTemplateChangedEventArgs : EventArgs
```


## Members

### IncomingMapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the MapView the incoming active template belongs to.</p>


```csharp
public MapView IncomingMapView { get; }
```
### IncomingTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the new active template.</p>


```csharp
public EditingTemplate IncomingTemplate { get; }
```
### OutgoingMapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the MapView the outgoing active template belongs to.</p>


```csharp
public MapView OutgoingMapView { get; }
```
### OutgoingTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ActiveTemplateChangedEventArgs.yml" sourcestartlinenumber="1">Gets the previous active template.</p>


```csharp
public EditingTemplate OutgoingTemplate { get; }
```


