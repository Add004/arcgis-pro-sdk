# RubbersheetByGeometries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByGeometries.yml" sourcestartlinenumber="1">Perform a rubbersheet operation using the specified geometries.</p>


## Object Signature

```csharp
public sealed class RubbersheetByGeometries : RubbersheetMethod
```


## Members

### RubbersheetByGeometries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByGeometries.yml" sourcestartlinenumber="1">Constructs a <xref href="ArcGIS.Desktop.Editing.RubbersheetByGeometries" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public RubbersheetByGeometries()
```
### AnchorPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByGeometries.yml" sourcestartlinenumber="1">Gets or sets the collection of points to use as anchor points for the rubbersheet.</p>


```csharp
public IEnumerable<MapPoint> AnchorPoints { get; set; }
```
### LimitedAdjustmentAreas

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByGeometries.yml" sourcestartlinenumber="1">Gets or sets the collection of polygons to use to limit the features in the rubbersheet operation.</p>


```csharp
public IEnumerable<Polygon> LimitedAdjustmentAreas { get; set; }
```
### LinkLines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetByGeometries.yml" sourcestartlinenumber="1">Gets or sets the collection of lines to use as vectors for the rubbersheet.</p>


```csharp
public IEnumerable<Polyline> LinkLines { get; set; }
```


