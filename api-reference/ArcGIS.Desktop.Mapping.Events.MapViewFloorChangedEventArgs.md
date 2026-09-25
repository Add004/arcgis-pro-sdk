# MapViewFloorChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewFloorChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapViewFloorChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapViewFloorChangedEventArgs : MapViewEventArgs
```


## Members

### CurrentFloorFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewFloorChangedEventArgs.yml" sourcestartlinenumber="1">Gets the current floor filter for the map view.</p>


```csharp
public CIMFloorFilterSettings CurrentFloorFilter { get; }
```
### PreviousFloorFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewFloorChangedEventArgs.yml" sourcestartlinenumber="1">Gets the previous floor filter for the map view.</p>


```csharp
public CIMFloorFilterSettings PreviousFloorFilter { get; }
```


