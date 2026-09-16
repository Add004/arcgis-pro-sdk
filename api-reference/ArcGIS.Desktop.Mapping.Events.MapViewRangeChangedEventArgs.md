# MapViewRangeChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapViewRangeChangedEventArgs : MapViewEventArgs
```


## Members

### CurrentRange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEventArgs.yml" sourcestartlinenumber="1">Gets the current range for the map view.</p>


```csharp
public RangeExtent CurrentRange { get; }
```
### PreviousRange

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewRangeChangedEventArgs.yml" sourcestartlinenumber="1">Gets the previous range for the map view.</p>


```csharp
public RangeExtent PreviousRange { get; }
```


