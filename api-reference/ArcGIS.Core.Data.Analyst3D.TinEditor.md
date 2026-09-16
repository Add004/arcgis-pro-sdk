# TinEditor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Represents an object for creating and modifying TINs.</p>


## Object Signature

```csharp
public class TinEditor : CoreObjectsBase, IDisposable
```


## Members

### TinEditor(TinDataset)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Creates a new TIN editor instance and puts it in edit mode. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEditor(TinDataset tinDataset)
```
### TinEditor(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Creates a new TIN editor instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEditor(Envelope extent)
```
### AddFromFeatureClass(FeatureClass, QueryFilter, Field, Field, TinSurfaceType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds features from a feature class to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddFromFeatureClass(FeatureClass featureClass, QueryFilter queryFilter, Field heightField, Field tagField, TinSurfaceType tinSurfaceType)
```
### AddGeometry(Geometry, TinSurfaceType, int, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds a geometry to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddGeometry(Geometry geometry, TinSurfaceType tinSurfaceType, int tagValue, double z)
```
### AddGeometryZ(Geometry, TinSurfaceType, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds a geometry to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddGeometryZ(Geometry geometry, TinSurfaceType tinSurfaceType, int tagValue)
```
### AddMassPoints(IEnumerable&lt;MapPoint&gt;, int, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds points as nodes to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddMassPoints(IEnumerable<MapPoint> points, int tagValue, double z, SpatialReference spatialReference = null)
```
### AddMassPointsZ(IEnumerable&lt;Coordinate3D&gt;, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds coordinates as nodes to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddMassPointsZ(IEnumerable<Coordinate3D> coordinates, int tagValue, SpatialReference spatialReference = null)
```
### AddMassPointsZ(IEnumerable&lt;MapPoint&gt;, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds points as nodes to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddMassPointsZ(IEnumerable<MapPoint> points, int tagValue, SpatialReference spatialReference = null)
```
### AddPointZ(MapPoint, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds a 3D point as a node to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int AddPointZ(MapPoint point, int tagValue)
```
### AddPolygons(IEnumerable&lt;Polygon&gt;, TinSurfaceType, int, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds polygons to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddPolygons(IEnumerable<Polygon> polygons, TinSurfaceType tinSurfaceType, int tagValue, double z, SpatialReference spatialReference = null)
```
### AddPolygonsZ(IEnumerable&lt;Polygon&gt;, TinSurfaceType, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds polygons to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddPolygonsZ(IEnumerable<Polygon> polygons, TinSurfaceType tinSurfaceType, int tagValue, SpatialReference spatialReference = null)
```
### AddPolylines(IEnumerable&lt;Polyline&gt;, TinSurfaceType, int, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds polylines to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddPolylines(IEnumerable<Polyline> polylines, TinSurfaceType tinSurfaceType, int tagValue, double z, SpatialReference spatialReference = null)
```
### AddPolylinesZ(IEnumerable&lt;Polyline&gt;, TinSurfaceType, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Adds polylines to the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddPolylinesZ(IEnumerable<Polyline> polylines, TinSurfaceType tinSurfaceType, int tagValue, SpatialReference spatialReference = null)
```
### CreateFromFeatureClass(FeatureClass, QueryFilter, Field, Field, TinSurfaceType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Creates a new TIN editor instance. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static TinEditor CreateFromFeatureClass(FeatureClass featureClass, QueryFilter queryFilter, Field heightField, Field tagField, TinSurfaceType tinSurfaceType)
```
### DeleteEdgeTagValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Deletes all edge tag values in the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteEdgeTagValues()
```
### DeleteNode(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Deletes the specified node. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteNode(int index)
```
### DeleteNodeTagValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Deletes all data node tag values. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteNodeTagValues()
```
### DeleteNodesOutsideDataArea()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Deletes all data nodes that are outside of the data area. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteNodesOutsideDataArea()
```
### DeleteTriangleTagValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Deletes all triangle tag values in the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteTriangleTagValues()
```
### IsInEditMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Indicates if the TIN editor is in edit mode.</p>


```csharp
public bool IsInEditMode { get; }
```
### SaveAs(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Saves the TIN to disk using the specified name. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveAs(string outputTinPath, bool overwrite)
```
### SaveEdits()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Saves edits to disk. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveEdits()
```
### SetEdgeTagValue(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the tag value of the specified triangle edge. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEdgeTagValue(int index, int tagValue)
```
### SetEdgeType(int, TinEdgeType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the edge type of the specified triangle edge. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEdgeType(int index, TinEdgeType edgeType)
```
### SetNodeTagValue(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the tag value of the specified node. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetNodeTagValue(int index, int tagValue)
```
### SetNodeZ(int, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the z-value of the specified node. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetNodeZ(int index, double zValue)
```
### SetSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets a copy of the input spatial reference in the TIN. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSpatialReference(SpatialReference spatialReference)
```
### SetToConstrainedDelaunay()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the triangulation method to constrained Delaunay from this point forward. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetToConstrainedDelaunay()
```
### SetTriangleInsideDataArea(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the specified triangle within the TIN interpolation zone. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetTriangleInsideDataArea(int index)
```
### SetTriangleOutsideDataArea(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the specified triangle outside the TIN interpolation zone. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetTriangleOutsideDataArea(int index)
```
### SetTriangleTagValue(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the tag value of the specified triangle. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetTriangleTagValue(int index, int tagValue)
```
### SetZFactor(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Sets the Z unit conversion factor for this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetZFactor(double zFactor)
```
### StartEditing()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Puts the TIN editor in edit mode. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool StartEditing()
```
### StopEditing(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEditor.yml" sourcestartlinenumber="1">Terminates edit mode. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool StopEditing(bool saveEdits)
```


