# BeforeSketchCompletedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs.yml" sourcestartlinenumber="1">Provides information about the geometry before a sketch is completed.</p>


## Object Signature

```csharp
public sealed class BeforeSketchCompletedEventArgs : EventArgs
```


## Members

### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the map view the sketch is completed on.</p>


```csharp
public MapView MapView { get; }
```
### SetSketchGeometry(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs.yml" sourcestartlinenumber="1">Sets the current geometry of the sketch without finishing it.</p>


```csharp
public void SetSketchGeometry(Geometry newSketch)
```
### Sketch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BeforeSketchCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the current sketch geometry.</p>


```csharp
public Geometry Sketch { get; }
```


