# ActiveMapViewChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ActiveMapViewChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.ActiveMapViewChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class ActiveMapViewChangedEventArgs : EventArgs
```


## Members

### ActiveMapViewChangedEventArgs(MapView, MapView)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ActiveMapViewChangedEventArgs.yml" sourcestartlinenumber="1">Constructs a new ActiveMapViewChangedEventArgs.</p>


```csharp
public ActiveMapViewChangedEventArgs(MapView incomingView, MapView outgoingView)
```
### IncomingView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ActiveMapViewChangedEventArgs.yml" sourcestartlinenumber="1">Gets the new active map view.</p>


```csharp
public MapView IncomingView { get; }
```
### OutgoingView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ActiveMapViewChangedEventArgs.yml" sourcestartlinenumber="1">Gets the previous active map view.</p>


```csharp
public MapView OutgoingView { get; }
```
### Refresh

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ActiveMapViewChangedEventArgs.yml" sourcestartlinenumber="1">Gets the refresh state.</p>


```csharp
public bool Refresh { get; }
```


