# SymbolFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Provides methods for creating symbols.</p>


## Object Signature

```csharp
public class SymbolFactory : ISymbolFactory
```


## Members

### ConstructFill()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a fill.  The default color is <xref href="ArcGIS.Desktop.Mapping.ColorFactory.GreyRGB" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CIMFill ConstructFill()
```
### ConstructGradientFill(CIMColor, CIMColor, GradientFillMethod, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a gradient fill between two colors. Either of the colors can be <xref href="ArcGIS.Core.CIM.CIMColor.NoColor" data-throw-if-not-resolved="false"></xref> to
allow the gradient to fade to or from transparency.</p>


```csharp
public CIMFill ConstructGradientFill(CIMColor color1, CIMColor color2, GradientFillMethod gradientFillMethod = 3, int interval = 36)
```
### ConstructGradientFill(CIMColorRamp, GradientFillMethod, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a gradient fill using the specififed color ramp.</p>


```csharp
public CIMFill ConstructGradientFill(CIMColorRamp colorRamp, GradientFillMethod gradientFillMethod = 3, int interval = 36)
```
### ConstructHatchFill(CIMColor, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a hatch fill of specific color, angle and separation.</p>


```csharp
public CIMFill ConstructHatchFill(CIMColor color, double angle, double separation)
```
### ConstructHatchFill(CIMStroke, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a hatch fill with the specified parameters.</p>


```csharp
public CIMFill ConstructHatchFill(CIMStroke lineStroke, double angle, double separation, double offset = 0)
```
### ConstructLineSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol()
```
### ConstructLineSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol of specific color.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol(CIMColor color)
```
### ConstructLineSymbol(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol of specific color and width.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol(CIMColor color, double width)
```
### ConstructLineSymbol(CIMColor, double, SimpleLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol of specific color, width and style.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol(CIMColor color, double width, SimpleLineStyle lineStyle)
```
### ConstructLineSymbol(CIMColor, double, SimpleLineStyle, Simple3DLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D line symbol of specific color, width and style.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D)
```
### ConstructLineSymbol(CIMColor, double, SimpleLineStyle, Simple3DLineStyle, Simple3DLineAnchor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D line symbol of specific color, width and style.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D, Simple3DLineAnchor anchor3D)
```
### ConstructLineSymbol(CIMStroke)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol from a stroke.</p>


```csharp
public CIMLineSymbol ConstructLineSymbol(CIMStroke stroke)
```
### ConstructMarker()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker()
```
### ConstructMarker(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker(CIMColor color)
```
### ConstructMarker(CIMColor, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D marker pf tje s[ecofoed cp;pr amd 3D marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker(CIMColor color, Simple3DMarkerStyle markerStyle)
```
### ConstructMarker(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color and size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker(CIMColor color, double size)
```
### ConstructMarker(CIMColor, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color, size and style.</p>


```csharp
public CIMMarker ConstructMarker(CIMColor color, double size, Polygon markerShape)
```
### ConstructMarker(CIMColor, double, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D marker of the specified color, size and 3D marker style.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker(CIMColor color, double size, Simple3DMarkerStyle markerStyle)
```
### ConstructMarker(CIMColor, double, SimpleMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color, size and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker(CIMColor color, double size, SimpleMarkerStyle markerStyle)
```
### ConstructMarker(CIMFill, CIMStroke, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of the specified shape, fill, outline, and size.</p>


```csharp
public CIMMarker ConstructMarker(CIMFill fill, CIMStroke outline, double size, Polygon markerShape)
```
### ConstructMarker(CIMPolygonSymbol, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of the specified fill style, size, and shape.</p>


```csharp
public CIMMarker ConstructMarker(CIMPolygonSymbol fillSymbol, double size, Polygon markerShape)
```
### ConstructMarker(CIMStroke, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of the stroke (&quot;outline&quot;), size, and shape.</p>


```csharp
public CIMMarker ConstructMarker(CIMStroke outline, double size, Polygon markerShape)
```
### ConstructMarker(Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D marker of the specified 3D marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarker(Simple3DMarkerStyle markerStyle)
```
### ConstructMarker(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
public CIMMarker ConstructMarker(int characterIndex, string fontFamily)
```
### ConstructMarker(int, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
public CIMMarker ConstructMarker(int characterIndex, string fontFamily, string fontStyle)
```
### ConstructMarker(int, string, string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
public CIMMarker ConstructMarker(int characterIndex, string fontFamily, string fontStyle, int size)
```
### ConstructMarker(int, string, string, int, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
public CIMMarker ConstructMarker(int characterIndex, string fontFamily, string fontStyle, int size, CIMColor color)
```
### ConstructMarkerFromBitmapSource(BitmapSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker from a bitmap source.</p>


```csharp
public CIMMarker ConstructMarkerFromBitmapSource(BitmapSource bitmapSource)
```
### ConstructMarkerFromFile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker from file. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker ConstructMarkerFromFile(string file)
```
### ConstructMarkerFromStream(Stream)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker from a stream.</p>


```csharp
public CIMMarker ConstructMarkerFromStream(Stream stream)
```
### ConstructMarkerShape(SimpleMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs the marker outline for the given marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polygon ConstructMarkerShape(SimpleMarkerStyle markerStyle)
```
### ConstructMaterial()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default material for a mesh.</p>


```csharp
public CIMMaterialSymbolLayer ConstructMaterial()
```
### ConstructMaterial(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default material for a mesh with the specified color.</p>


```csharp
public CIMMaterialSymbolLayer ConstructMaterial(CIMColor color)
```
### ConstructMaterial(CIMColor, MaterialMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default material for a mesh with the specified color and material mode.</p>


```csharp
public CIMMaterialSymbolLayer ConstructMaterial(CIMColor color, MaterialMode materialMode)
```
### ConstructMeshEdge()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh edge for a mesh.</p>


```csharp
public CIMMeshEdge ConstructMeshEdge()
```
### ConstructMeshEdge(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh edge for a mesh with the specified color.</p>


```csharp
public CIMMeshEdge ConstructMeshEdge(CIMColor color)
```
### ConstructMeshSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol for a multipatch using the default mesh symbol.</p>


```csharp
public CIMMeshSymbol ConstructMeshSymbol()
```
### ConstructMeshSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol with the specified color.</p>


```csharp
public CIMMeshSymbol ConstructMeshSymbol(CIMColor color)
```
### ConstructMeshSymbol(CIMColor, MaterialMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol with the specified color and material mode.</p>


```csharp
public CIMMeshSymbol ConstructMeshSymbol(CIMColor color, MaterialMode materialMode)
```
### ConstructMeshSymbol(CIMMaterialSymbolLayer, CIMMeshEdge)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol with the specified material and edge.</p>


```csharp
public CIMMeshSymbol ConstructMeshSymbol(CIMMaterialSymbolLayer material, CIMMeshEdge edge)
```
### ConstructPictureFill(string, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a picture fill with the specified parameters.</p>


```csharp
public CIMFill ConstructPictureFill(string fileName, double size)
```
### ConstructPointSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol()
```
### ConstructPointSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(CIMColor color)
```
### ConstructPointSymbol(CIMColor, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color and 3d marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(CIMColor color, Simple3DMarkerStyle style)
```
### ConstructPointSymbol(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color and size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(CIMColor color, double size)
```
### ConstructPointSymbol(CIMColor, double, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color, size and 3d marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(CIMColor color, double size, Simple3DMarkerStyle style)
```
### ConstructPointSymbol(CIMColor, double, SimpleMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color, size and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(CIMColor color, double size, SimpleMarkerStyle style)
```
### ConstructPointSymbol(CIMMarker)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol from a marker.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(CIMMarker marker)
```
### ConstructPointSymbol(Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific 3d marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol ConstructPointSymbol(Simple3DMarkerStyle style)
```
### ConstructPolygonSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol()
```
### ConstructPolygonSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color)
```
### ConstructPolygonSymbol(CIMColor, SimpleFillStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color and style.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleFillStyle fillStyle)
```
### ConstructPolygonSymbol(CIMColor, SimpleFillStyle, CIMStroke)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color, style and outline.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleFillStyle fillStyle, CIMStroke outline)
```
### ConstructPolygonSymbol(CIMColor, SimpleStipplePattern)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color and stipple pattern.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleStipplePattern stipplePattern)
```
### ConstructPolygonSymbol(CIMColor, SimpleStipplePattern, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color, fill color, and stipple pattern.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleStipplePattern stipplePattern, CIMColor fillColor)
```
### ConstructPolygonSymbol(CIMFill, CIMStroke)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol from a fill and an outline.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMFill fill, CIMStroke outline)
```
### ConstructPolygonSymbol(CIMFill, CIMStroke, CIMColor, SimpleStipplePattern)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol with a specific fill, stroke, and stipple pattern.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMFill fill, CIMStroke outline, CIMColor color, SimpleStipplePattern stipplePattern)
```
### ConstructPolygonSymbol(CIMFill, CIMStroke, CIMMarker)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol from a fill and an outline.</p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbol(CIMFill fill, CIMStroke outline, CIMMarker pointMarker)
```
### ConstructPolygonSymbolWithPenInkCrossHatch(CIMColor, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol in the specified color representing a pen and ink
cross hatch effect.
See <a href="https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/">Pen and Ink styles</a></p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbolWithPenInkCrossHatch(CIMColor color, bool includeBorder)
```
### ConstructPolygonSymbolWithPenInkRipple(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol in the specified color representing a pen and ink ripple water fill.
See <a href="https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/">Pen and Ink styles</a></p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbolWithPenInkRipple(CIMColor color)
```
### ConstructPolygonSymbolWithPenInkStipple(CIMColor, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol in the specified color representing a pen and ink stipple effect.
See <a href="https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/">Pen and Ink styles</a></p>


```csharp
public CIMPolygonSymbol ConstructPolygonSymbolWithPenInkStipple(CIMColor color, bool includeBorder)
```
### ConstructProceduralSymbol(string, FeatureLayer, IEnumerable&lt;CIMPrimitiveOverride&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Create a symbol reference with a procedural symbol layer for a rule package. This
method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMSymbolReference ConstructProceduralSymbol(string rulePackagePath, FeatureLayer featureLayer, IEnumerable<CIMPrimitiveOverride> overrides = null)
```
### ConstructSolidFill(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a solid fill of specific color.</p>


```csharp
public CIMFill ConstructSolidFill(CIMColor color)
```
### ConstructStroke()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke.</p>


```csharp
public CIMStroke ConstructStroke()
```
### ConstructStroke(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke of specific color.</p>


```csharp
public CIMStroke ConstructStroke(CIMColor color)
```
### ConstructStroke(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke of specific color and width.</p>


```csharp
public CIMStroke ConstructStroke(CIMColor color, double width)
```
### ConstructStroke(CIMColor, double, SimpleLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke of specific color, width and style.</p>


```csharp
public CIMStroke ConstructStroke(CIMColor color, double width, SimpleLineStyle lineStyle)
```
### ConstructStroke(CIMColor, double, SimpleLineStyle, Simple3DLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D stroke of specific color, width and style.</p>


```csharp
public CIMStroke ConstructStroke(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D)
```
### ConstructStroke(CIMColor, double, SimpleLineStyle, Simple3DLineStyle, Simple3DLineAnchor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D stroke of specific color, width and style.</p>


```csharp
public CIMStroke ConstructStroke(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D, Simple3DLineAnchor anchor3D)
```
### ConstructTextSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol()
```
### ConstructTextSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(CIMColor color)
```
### ConstructTextSymbol(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color and size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(CIMColor color, double size)
```
### ConstructTextSymbol(CIMColor, double, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color, size, and font family name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(CIMColor color, double size, string fontFamilyName)
```
### ConstructTextSymbol(CIMColor, double, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color, size, font family name and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(CIMColor color, double size, string fontFamilyName, string fontStyleName)
```
### ConstructTextSymbol(CIMPolygonSymbol, double, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its polygon symbol, size, and font family name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(CIMPolygonSymbol symbol, double size, string fontFamilyName)
```
### ConstructTextSymbol(CIMPolygonSymbol, double, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its polygon symbol, size, font family name and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(CIMPolygonSymbol symbol, double size, string fontFamilyName, string fontStyleName)
```
### ConstructTextSymbol(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(double size)
```
### ConstructTextSymbol(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its font family name. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(string fontFamilyName)
```
### ConstructTextSymbol(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color, size, font family name and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol ConstructTextSymbol(string fontFamilyName, string fontStyleName)
```
### ConstructWaterFill(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a water fill of specific color.</p>


```csharp
public CIMFill ConstructWaterFill(CIMColor color)
```
### ConstructWaterFill(CIMColor, WaterbodySize, WaveStrength)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Constructs a water fill of specific color, waterbody size and wave strength.</p>


```csharp
public CIMFill ConstructWaterFill(CIMColor color, WaterbodySize waterBodySize, WaveStrength waveStrength)
```
### DefaultFill

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMFill" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMFill DefaultFill { get; }
```
### DefaultFont

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the application default font family name and style.
This property must be accessed on the MCT. Use QueuedTask.Run.</p>


```csharp
public (string fontName, string styleName) DefaultFont { get; }
```
### DefaultLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the  <xref href="ArcGIS.Core.CIM.CIMLineSymbol" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMLineSymbol DefaultLineSymbol { get; }
```
### DefaultMarker

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMMarker" data-throw-if-not-resolved="false"></xref> with default properties. This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMarker DefaultMarker { get; }
```
### DefaultMaterial

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMMaterialSymbolLayer" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMMaterialSymbolLayer DefaultMaterial { get; }
```
### DefaultMeshEdge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMMeshEdge" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMMeshEdge DefaultMeshEdge { get; }
```
### DefaultMeshSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMMeshSymbol" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMMeshSymbol DefaultMeshSymbol { get; }
```
### DefaultPointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMPointSymbol" data-throw-if-not-resolved="false"></xref> with default properties. This property must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol DefaultPointSymbol { get; }
```
### DefaultPolygonSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMPolygonSymbol" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMPolygonSymbol DefaultPolygonSymbol { get; }
```
### DefaultSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets a default size for <xref href="ArcGIS.Core.CIM.CIMMarker" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double DefaultSize { get; }
```
### DefaultStroke

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMStroke" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMStroke DefaultStroke { get; }
```
### DefaultTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMTextSymbol" data-throw-if-not-resolved="false"></xref> with default properties.</p>


```csharp
public CIMTextSymbol DefaultTextSymbol { get; }
```
### DefaultWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets a default width for <xref href="ArcGIS.Core.CIM.CIMStroke" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double DefaultWidth { get; }
```
### GenerateImage(CIMPointSymbol, OutputImageFormat, double, bool, double, long, long, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Generates an image for point symbols.</p>


```csharp
public MemoryStream GenerateImage(CIMPointSymbol pointSymbol, OutputImageFormat imageFormat, double scaleFactor, bool centerAnchorPoint, double dpi, long width, long height, CIMColor backgroundColor)
```
### GetAvailableFonts()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the list of available fonts in the application for the Pro session.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<(string fontName, List<string> fontStyles)> GetAvailableFonts()
```
### GetDictionarySymbol(string, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Builds a symbol from a dictionary. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMSymbol GetDictionarySymbol(string dictionaryName, Dictionary<string, object> values)
```
### GetRulePackageDescription(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Populate the associated rule package description. This method must be called on
the MCT. Use QueuedTask.Run.</p>


```csharp
public RulePackageDescription GetRulePackageDescription(string rulePackagePath)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Gets the singleton instance of ISymbolFactory.</p>


```csharp
public static ISymbolFactory Instance { get; }
```
### IsFontAvailable(string, string, FontType, List&lt;CIMFontVariation&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Check if a specific font is available in the application for the Pro session.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsFontAvailable(string fontName, string fontStyle, FontType fontType, List<CIMFontVariation> fontVariationSettings)
```
### LayerIsCompatibleWithRulePackage(string, FeatureLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Checks the compatibility of the rule package geometry with the feature layer shape type for use as a renderer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool LayerIsCompatibleWithRulePackage(string rulePackagePath, FeatureLayer featureLayer)
```
### ShapeTypeSupportedWithRulePackage(FeatureLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolFactory.yml" sourcestartlinenumber="1">Checks if the underlying shape type of the layer features is supported for use with rule package renderers.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ShapeTypeSupportedWithRulePackage(FeatureLayer featureLayer)
```


