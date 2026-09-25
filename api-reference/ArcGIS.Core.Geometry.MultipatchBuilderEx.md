# MultipatchBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class MultipatchBuilderEx : GeometryBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Use the MultipatchBuilderEx class to to create a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> geometry. Use the
<xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method to get the <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> geometry from the builder.</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="6">The MultipatchBuilderEx class allows you to edit properties including the material
and texture that will be in the resulting <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="11">The MultipatchBuilderEx methods can be called on any thread.</p>


## Members

### MultipatchBuilderEx(Multipatch)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> class from the specified <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MultipatchBuilderEx(Multipatch multipatch)
```
### MultipatchBuilderEx(MultipatchBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> class from the specified <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MultipatchBuilderEx(MultipatchBuilderEx multipatchBuilderEx)
```
### MultipatchBuilderEx(MultipatchConstructType, MapPoint, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> class.
Use this constructor to create a cube, tetrahedron, diamond or hexagon centered around the <code class="paramref">centerPt</code> of the specified <code class="paramref">size</code>.</p>


```csharp
public MultipatchBuilderEx(MultipatchConstructType constructType, MapPoint centerPt, double size, SpatialReference spatialReference = null)
```
### MultipatchBuilderEx(MultipatchConstructType, MapPoint, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> class.
Use this constructor to create a cylinder, sphere, sphere frame or cone centered around the <code class="paramref">centerPt</code> of the specified <code class="paramref">size</code>
and <code class="paramref">quality</code>.</p>


```csharp
public MultipatchBuilderEx(MultipatchConstructType constructType, MapPoint centerPt, double size, double quality, SpatialReference spatialReference = null)
```
### MultipatchBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates an empty instance of the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipatchBuilderEx(SpatialReference spatialReference = null)
```
### AddPoint(int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to add a point to the specified <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void AddPoint(int patchIndex, MapPoint point)
```
### CreateMultipatch(Multipatch, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Convenience method to quickly create a new instance of the <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from the specified multipatch.</p>


```csharp
public static Multipatch CreateMultipatch(Multipatch multipatch, SpatialReference spatialReference = null)
```
### CreateMultipatch(MultipatchBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Convenience method to quickly create a new instance of the <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from the specified multipatch builder.</p>


```csharp
public static Multipatch CreateMultipatch(MultipatchBuilderEx multipatchBuilderEx, SpatialReference spatialReference = null)
```
### CreateMultipatch(MultipatchConstructType, MapPoint, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Convenience method to quickly create a new <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> object.
Use this constructor to create a cube, tetrahedron, diamond or hexagon centered around the <code class="paramref">centerPt</code> of the specified <code class="paramref">size</code>.</p>


```csharp
public static Multipatch CreateMultipatch(MultipatchConstructType constructType, MapPoint centerPt, double size, SpatialReference spatialReference = null)
```
### CreateMultipatch(MultipatchConstructType, MapPoint, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Convenience method to quickly create a new <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> object.
Use this constructor to create a cylinder, sphere, sphere frame or cone centered around the <code class="paramref">centerPt</code> of the specified <code class="paramref">size</code>
and <code class="paramref">quality</code>.</p>


```csharp
public static Multipatch CreateMultipatch(MultipatchConstructType constructType, MapPoint centerPt, double size, double quality, SpatialReference spatialReference = null)
```
### CreateMultipatch(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Convenience method to quickly create an empty instance of the <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipatch CreateMultipatch(SpatialReference spatialReference = null)
```
### From3DModelFile(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from a supported 3D model file.</p>


```csharp
public static Multipatch From3DModelFile(string filePath, SpatialReference spatialReference = null)
```
### From3DObjectXML(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from a 3D object XML representation.</p>


```csharp
public static Multipatch From3DObjectXML(string xml)
```
### FromBinaryXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from a binary XML string representation.</p>


```csharp
public static Multipatch FromBinaryXml(string xmlString)
```
### FromEsriShape(byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from an Esri shape buffer.</p>


```csharp
public static Multipatch FromEsriShape(byte[] esriShapeBuffer, SpatialReference spatialReference = null)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> class from an XML string representation.</p>


```csharp
public static Multipatch FromXml(string xmlString)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### GetPatchPointCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to return the number of vertices in the specified <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int GetPatchPointCount(int patchIndex)
```
### GetPoint(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to get the <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> from the specified patch at the specified point index.</p>


```csharp
public MapPoint GetPoint(int patchIndex, int pointIndex)
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes ID-values also known as ID-awareness.</p>


```csharp
public override bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes M-values also known as M-awareness.</p>


```csharp
public override bool HasM { get; set; }
```
### HasNormals

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes normals.</p>


```csharp
public bool HasNormals { get; set; }
```
### HasTextureCoords2D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets a value indicating if any of the patches in the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> has 2D texture coordinates.</p>


```csharp
public bool HasTextureCoords2D { get; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets a value indicating if the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes Z-values also known as Z-awareness.</p>


```csharp
public override bool HasZ { get; set; }
```
### InsertPoint(int, int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to insert a point in the specified <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void InsertPoint(int patchIndex, int beforePointIndex, MapPoint point)
```
### InsertPoints(int, int, IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to insert a collection of points into the specified <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void InsertPoints(int patchIndex, int beforePointIndex, IEnumerable<MapPoint> points)
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Returns true if this instance is empty (has no patches).</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(MultipatchBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of MultipatchBuilderEx to the other for equality.</p>


```csharp
public bool IsEqual(MultipatchBuilderEx other)
```
### MakePatch(PatchType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Creates an empty <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref> that inherits attribute awareness from this builder.</p>


```csharp
public Patch MakePatch(PatchType patchType)
```
### Patches

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of patches for this instance.</p>


```csharp
public IList<Patch> Patches { get; set; }
```
### QueryPatchIndicesWithMaterial(Material)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Returns an array of patch indices that reference the given <xref href="ArcGIS.Core.Geometry.Material" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public int[] QueryPatchIndicesWithMaterial(Material material)
```
### QueryPatchIndicesWithTexture(TextureResource)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Returns an array of patch indices that reference the given <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public int[] QueryPatchIndicesWithTexture(TextureResource textureResource)
```
### RemovePoints(int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to remove points from the specified <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref></p>


```csharp
public void RemovePoints(int patchIndex, int fromIndex, int toIndex)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Sets this instance to empty.</p>


```csharp
public override void SetEmpty()
```
### SetPoint(int, int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A convenience method to update the components of a point in the specified <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetPoint(int patchIndex, int pointIndex, MapPoint point)
```
### SynchronizeAttributeAwareness()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Synchronizes attribute awareness of <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx.Patches" data-throw-if-not-resolved="false"></xref> to match attribute awareness of the <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool SynchronizeAttributeAwareness()
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> instance representing the current state of this builder.</p>


```csharp
public override Multipatch ToGeometry()
```


