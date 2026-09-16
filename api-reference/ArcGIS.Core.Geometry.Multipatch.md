# Multipatch

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">A class representing a multipatch.</p>


## Object Signature

```csharp
public sealed class Multipatch : Geometry
```

## Remarks

<p>
     A Multipatch is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
     its shape once it is created. 
     </p>
<p>A multipatch is a series of 3-dimensional surfaces. The surfaces may be represented by triangle strips, 
     triangles fans, groups of triangles or groups of rings. In a multipatch there is one triangle strip, triangle fan, or groups of triangles per surface, 
     whereas there can be one or more rings per surface. A single multipatch may comprise combinations of triangle strips, triangle fans, groups of triangles, 
     or groups of rings. 
     </p>
<p>Each part in a multipatch is called a patch. A patch can be a triangle strip, triangle fan, a group of triangles, or a ring. 
     See <xref href="ArcGIS.Core.Geometry.PatchType" data-throw-if-not-resolved="false"></xref> for more information on patch types.
     </p>


## Members

### Copy3DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Copy all the coordinates of all the parts to a list of coordinates.</p>


```csharp
public IReadOnlyList<Coordinate3D> Copy3DCoordinatesToList()
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of this instance.</p>


```csharp
public override Envelope Extent { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the geometry type. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### GetMaterialColor(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the color of the specified material.</p>


```csharp
public Color GetMaterialColor(int materialIndex)
```
### GetMaterialEdgeColor(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the edge color of the specified material.</p>


```csharp
public Color GetMaterialEdgeColor(int materialIndex)
```
### GetMaterialEdgeWidth(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the edge width of the specified material.</p>


```csharp
public int GetMaterialEdgeWidth(int materialIndex)
```
### GetMaterialShininess(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the shininess of the specified material.</p>


```csharp
public int GetMaterialShininess(int materialIndex)
```
### GetMaterialTexture(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a byte buffer representing the texture image for the specifed material.</p>


```csharp
public byte[] GetMaterialTexture(int materialIndex)
```
### GetMaterialTextureBytesPerPixel(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of bytes per pixel of the texture contained in the specified material.</p>


```csharp
public int GetMaterialTextureBytesPerPixel(int materialIndex)
```
### GetMaterialTextureColumnCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of columns (width in pixels) of the texture image contained in the specified material.</p>


```csharp
public int GetMaterialTextureColumnCount(int materialIndex)
```
### GetMaterialTextureCompressionType(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the compression type of the byte buffer for the texture of the specified material.</p>


```csharp
public TextureCompressionType GetMaterialTextureCompressionType(int materialIndex)
```
### GetMaterialTextureRowCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of rows (height in pixels) of the texture contained in the specified material index.</p>


```csharp
public int GetMaterialTextureRowCount(int materialIndex)
```
### GetMaterialTransparencyPercent(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the overall transparency in percent (truncated as an integer) of the specified material.</p>


```csharp
public int GetMaterialTransparencyPercent(int materialIndex)
```
### GetPatchMaterialIndex(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the index of the material for the specified patch (part).</p>


```csharp
public int GetPatchMaterialIndex(int patchIndex)
```
### GetPatchNormal(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the normal coordinate for the specified patch (part) at the point index.</p>


```csharp
public Coordinate3D GetPatchNormal(int patchIndex, int pointIndex)
```
### GetPatchNormals(int, ref ICollection&lt;Coordinate3D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a collection of coordinates representing the vertices of the normals for the specified patch (part).</p>


```csharp
public void GetPatchNormals(int patchIndex, ref ICollection<Coordinate3D> normals)
```
### GetPatchPointCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of points for the specified patch (part).</p>


```csharp
public int GetPatchPointCount(int patchIndex)
```
### GetPatchPriority(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value representing the priority of the specified patch (part).</p>


```csharp
public int GetPatchPriority(int patchIndex)
```
### GetPatchStartPointIndex(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets index of the start point into this multipatch's point collection for the specified patch (part).</p>


```csharp
public int GetPatchStartPointIndex(int patchIndex)
```
### GetPatchTextureCoordinate(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the texture coordinate for the specified patch (part) at the point index.</p>


```csharp
public Coordinate2D GetPatchTextureCoordinate(int patchIndex, int pointIndex)
```
### GetPatchTextureCoordinates(int, ref ICollection&lt;Coordinate2D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a collection of coordinates representing the texture coordinates for the specified patch (part).</p>


```csharp
public void GetPatchTextureCoordinates(int patchIndex, ref ICollection<Coordinate2D> textureCoordinates)
```
### GetPatchTextureVertexCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of texture coordinates for the specified patch (part).</p>


```csharp
public int GetPatchTextureVertexCount(int patchIndex)
```
### GetPatchType(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the patch type for the specified patch (part).</p>


```csharp
public PatchType GetPatchType(int patchIndex)
```
### HasMaterials

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value indicating if this multipatch has materials.</p>


```csharp
public bool HasMaterials { get; }
```
### HasNormals

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value indicating if this multipatch has normals.</p>


```csharp
public bool HasNormals { get; }
```
### HasTextures

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value indicating if this multipatch has texture coordinates.</p>


```csharp
public bool HasTextures { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this instance is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(Multipatch)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> for equality.</p>


```csharp
public bool IsEqual(Multipatch multipatch)
```
### IsEqual(Multipatch, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Compares two multipatches for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Multipatch multipatch, double tolerance)
```
### IsMaterialCullBackFace(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value representing if back-face culling is persisted as a property of the specified material.</p>


```csharp
public bool IsMaterialCullBackFace(int materialIndex)
```
### IsMaterialTextured(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a value indicating if the specified material contains a texture image.</p>


```csharp
public bool IsMaterialTextured(int materialIndex)
```
### MaterialCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of materials in this multipatch.</p>


```csharp
public int MaterialCount { get; }
```
### PartCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the number of parts (also called patches) in this instance.</p>


```csharp
public int PartCount { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the count of all points in all parts for this instance.</p>


```csharp
public override int PointCount { get; }
```
### Points

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets a collection of points representing the vertices of all the parts.</p>


```csharp
public ReadOnlyPointCollection Points { get; }
```
### TextureVertexCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Gets the total number of texture coordinates in this multipatch.</p>


```csharp
public int TextureVertexCount { get; }
```
### To3DObjectXML(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Get a 3D object XML representation of this instance in the format provided.</p>


```csharp
public string To3DObjectXML(string format)
```
### ToBinaryXml()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Serializes this geometry instance into an ArcGIS binary XML geometry representation.</p>


```csharp
public string ToBinaryXml()
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Converts this Multipatch into an Esri shape formatted binary byte buffer.</p>


```csharp
public override byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">Converts this Multipatch into an Esri shape formatted binary byte buffer and returns the size of the shapeBuffer.</p>


```csharp
public override long ToEsriShape(ref byte[] shapeBuffer)
```


