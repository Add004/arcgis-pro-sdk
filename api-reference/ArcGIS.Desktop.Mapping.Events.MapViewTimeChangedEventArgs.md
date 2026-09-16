# MapViewTimeChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewTimeChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapViewTimeChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapViewTimeChangedEventArgs : MapViewEventArgs
```


## Members

### CurrentTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewTimeChangedEventArgs.yml" sourcestartlinenumber="1">Gets the current time for the map view.</p>


```csharp
public TimeRange CurrentTime { get; }
```
### PreviousTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapViewTimeChangedEventArgs.yml" sourcestartlinenumber="1">Gets the previous time for the map view.</p>


```csharp
public TimeRange PreviousTime { get; }
```


