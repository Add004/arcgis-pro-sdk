# SketchCompletedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCompletedEventArgs.yml" sourcestartlinenumber="1">Provides information about the geometry when a sketch is completed.</p>


## Object Signature

```csharp
public sealed class SketchCompletedEventArgs : EventArgs
```


## Members

### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the map view the sketch originated on.</p>


```csharp
public MapView MapView { get; }
```
### Sketch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the final sketch geometry.</p>


```csharp
public Geometry Sketch { get; }
```


