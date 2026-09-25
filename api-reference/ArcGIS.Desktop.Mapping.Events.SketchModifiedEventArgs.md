# SketchModifiedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchModifiedEventArgs.yml" sourcestartlinenumber="1">Provides information about the geometry when a sketch is modified.</p>


## Object Signature

```csharp
public sealed class SketchModifiedEventArgs : EventArgs
```


## Members

### CurrentSketch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchModifiedEventArgs.yml" sourcestartlinenumber="1">Gets the current sketch geometry.</p>


```csharp
public Geometry CurrentSketch { get; }
```
### IsUndo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchModifiedEventArgs.yml" sourcestartlinenumber="1">Gets if the sketch operation initiated from the undo stack?</p>


```csharp
public bool IsUndo { get; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchModifiedEventArgs.yml" sourcestartlinenumber="1">Gets the map view the sketch change originated on.</p>


```csharp
public MapView MapView { get; }
```
### PreviousSketch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchModifiedEventArgs.yml" sourcestartlinenumber="1">Gets the sketch geometry before the modification.</p>


```csharp
public Geometry PreviousSketch { get; }
```
### SketchOperationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.SketchModifiedEventArgs.yml" sourcestartlinenumber="1">Gets the sketch operation which caused this SketchModifiedEvent to fire.</p>


```csharp
public SketchOperationType SketchOperationType { get; }
```


