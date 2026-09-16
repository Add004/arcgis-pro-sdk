# MapPropertyChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapPropertyChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapPropertyChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapPropertyChangedEventArgs : EventArgs
```


## Members

### MapPropertyChangedEventArgs(IEnumerable&lt;MapEventHint&gt;, IEnumerable&lt;Map&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapPropertyChangedEventArgs.yml" sourcestartlinenumber="1">Constructs a new MapPropertyChangedEventArgs.</p>


```csharp
public MapPropertyChangedEventArgs(IEnumerable<MapEventHint> properties, IEnumerable<Map> maps)
```
### EventHints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapPropertyChangedEventArgs.yml" sourcestartlinenumber="1">Gets the list of properties that are modified.</p>


```csharp
public IList<MapEventHint> EventHints { get; }
```
### Maps

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapPropertyChangedEventArgs.yml" sourcestartlinenumber="1">Gets the list of maps whose properties are modified.</p>


```csharp
public IList<Map> Maps { get; }
```


