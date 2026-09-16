# ISymbolFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Symbol Factory interface for creating symbols. See <xref href="ArcGIS.Desktop.Mapping.SymbolFactory" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public interface ISymbolFactory
```


## Members

### ConstructFill()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a fill.  The default color is <xref href="ArcGIS.Desktop.Mapping.ColorFactory.GreyRGB" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
CIMFill ConstructFill()
```
### ConstructGradientFill(CIMColor, CIMColor, GradientFillMethod, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a gradient fill between two colors using the specified gradient fill method.</p>


```csharp
CIMFill ConstructGradientFill(CIMColor color1, CIMColor color2, GradientFillMethod gradientFillMethod = 3, int interval = 36)
```
### ConstructGradientFill(CIMColorRamp, GradientFillMethod, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a gradient fill using the specififed color ramp and gradient fill method.</p>


```csharp
CIMFill ConstructGradientFill(CIMColorRamp colorRamp, GradientFillMethod gradientFillMethod = 3, int interval = 36)
```
### ConstructHatchFill(CIMColor, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a hatch fill of specific color, angle and separation.</p>


```csharp
CIMFill ConstructHatchFill(CIMColor color, double angle, double separation)
```
### ConstructHatchFill(CIMStroke, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a hatch fill with the specified parameters.</p>


```csharp
CIMFill ConstructHatchFill(CIMStroke lineStroke, double angle, double separation, double offset)
```
### ConstructLineSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol.</p>


```csharp
CIMLineSymbol ConstructLineSymbol()
```
### ConstructLineSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol of specific color.</p>


```csharp
CIMLineSymbol ConstructLineSymbol(CIMColor color)
```
### ConstructLineSymbol(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol of specific color and width.</p>


```csharp
CIMLineSymbol ConstructLineSymbol(CIMColor color, double width)
```
### ConstructLineSymbol(CIMColor, double, SimpleLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol of specific color, width and style.</p>


```csharp
CIMLineSymbol ConstructLineSymbol(CIMColor color, double width, SimpleLineStyle lineStyle)
```
### ConstructLineSymbol(CIMColor, double, SimpleLineStyle, Simple3DLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D line symbol of specific color, width and style.</p>


```csharp
CIMLineSymbol ConstructLineSymbol(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D)
```
### ConstructLineSymbol(CIMColor, double, SimpleLineStyle, Simple3DLineStyle, Simple3DLineAnchor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D line symbol of specific color, width and style.</p>


```csharp
CIMLineSymbol ConstructLineSymbol(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D, Simple3DLineAnchor anchor3D)
```
### ConstructLineSymbol(CIMStroke)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a line symbol from a stroke.</p>


```csharp
CIMLineSymbol ConstructLineSymbol(CIMStroke stroke)
```
### ConstructMarker()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMMarker ConstructMarker()
```
### ConstructMarker(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMMarker ConstructMarker(CIMColor color)
```
### ConstructMarker(CIMColor, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D marker of the specified color and 3D marker style.</p>


```csharp
CIMMarker ConstructMarker(CIMColor color, Simple3DMarkerStyle markerStyle)
```
### ConstructMarker(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color and size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMMarker ConstructMarker(CIMColor color, double size)
```
### ConstructMarker(CIMColor, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color, size and style.</p>


```csharp
CIMMarker ConstructMarker(CIMColor color, double size, Polygon markerShape)
```
### ConstructMarker(CIMColor, double, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D marker of the specified color, size and 3D marker style.</p>


```csharp
CIMMarker ConstructMarker(CIMColor color, double size, Simple3DMarkerStyle markerStyle)
```
### ConstructMarker(CIMColor, double, SimpleMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of specific color, size and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMMarker ConstructMarker(CIMColor color, double size, SimpleMarkerStyle markerStyle)
```
### ConstructMarker(CIMFill, CIMStroke, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of the specified shape, fill, outline, and size.</p>


```csharp
CIMMarker ConstructMarker(CIMFill fill, CIMStroke outline, double size, Polygon markerShape)
```
### ConstructMarker(CIMPolygonSymbol, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of the specified fill style, size, and shape.</p>


```csharp
CIMMarker ConstructMarker(CIMPolygonSymbol fillSymbol, double size, Polygon markerShape)
```
### ConstructMarker(CIMStroke, double, Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker of the stroke (&quot;outline&quot;), size, and shape.</p>


```csharp
CIMMarker ConstructMarker(CIMStroke outline, double size, Polygon markerShape)
```
### ConstructMarker(Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D marker of the specified 3D marker style.</p>


```csharp
CIMMarker ConstructMarker(Simple3DMarkerStyle markerStyle)
```
### ConstructMarker(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
CIMMarker ConstructMarker(int characterIndex, string fontFamily)
```
### ConstructMarker(int, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
CIMMarker ConstructMarker(int characterIndex, string fontFamily, string fontStyle)
```
### ConstructMarker(int, string, string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
CIMMarker ConstructMarker(int characterIndex, string fontFamily, string fontStyle, int size)
```
### ConstructMarker(int, string, string, int, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a character marker.</p>


```csharp
CIMMarker ConstructMarker(int characterIndex, string fontFamily, string fontStyle, int size, CIMColor color)
```
### ConstructMarkerFromBitmapSource(BitmapSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker from a bitmap source.</p>


```csharp
CIMMarker ConstructMarkerFromBitmapSource(BitmapSource bitmapSource)
```
### ConstructMarkerFromFile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker from file. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMMarker ConstructMarkerFromFile(string file)
```
### ConstructMarkerFromStream(Stream)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a marker from a stream.</p>


```csharp
CIMMarker ConstructMarkerFromStream(Stream stream)
```
### ConstructMarkerShape(SimpleMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs the marker outline for the given marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Polygon ConstructMarkerShape(SimpleMarkerStyle markerStyle)
```
### ConstructMaterial()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default material for a mesh.</p>


```csharp
CIMMaterialSymbolLayer ConstructMaterial()
```
### ConstructMaterial(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default material for a mesh with the specified color.</p>


```csharp
CIMMaterialSymbolLayer ConstructMaterial(CIMColor color)
```
### ConstructMaterial(CIMColor, MaterialMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default material for a mesh with the specified color and material mode.</p>


```csharp
CIMMaterialSymbolLayer ConstructMaterial(CIMColor color, MaterialMode materialMode)
```
### ConstructMeshEdge()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh edge for a mesh.</p>


```csharp
CIMMeshEdge ConstructMeshEdge()
```
### ConstructMeshEdge(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh edge for a mesh with the specified color.</p>


```csharp
CIMMeshEdge ConstructMeshEdge(CIMColor color)
```
### ConstructMeshSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol for a multipatch using the default mesh symbol.</p>


```csharp
CIMMeshSymbol ConstructMeshSymbol()
```
### ConstructMeshSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol with the specified color.</p>


```csharp
CIMMeshSymbol ConstructMeshSymbol(CIMColor color)
```
### ConstructMeshSymbol(CIMColor, MaterialMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol with the specified color and material mode.</p>


```csharp
CIMMeshSymbol ConstructMeshSymbol(CIMColor color, MaterialMode materialMode)
```
### ConstructMeshSymbol(CIMMaterialSymbolLayer, CIMMeshEdge)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a mesh symbol with the specified material and edge.</p>


```csharp
CIMMeshSymbol ConstructMeshSymbol(CIMMaterialSymbolLayer material, CIMMeshEdge edge)
```
### ConstructPictureFill(string, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a picture fill with the specified parameters.</p>


```csharp
CIMFill ConstructPictureFill(string fileName, double size)
```
### ConstructPointSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol()
```
### ConstructPointSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(CIMColor color)
```
### ConstructPointSymbol(CIMColor, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color and 3d marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(CIMColor color, Simple3DMarkerStyle style)
```
### ConstructPointSymbol(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color and size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(CIMColor color, double size)
```
### ConstructPointSymbol(CIMColor, double, Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color, size and 3d marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(CIMColor color, double size, Simple3DMarkerStyle style)
```
### ConstructPointSymbol(CIMColor, double, SimpleMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific color, size and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(CIMColor color, double size, SimpleMarkerStyle style)
```
### ConstructPointSymbol(CIMMarker)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol from a marker.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(CIMMarker marker)
```
### ConstructPointSymbol(Simple3DMarkerStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a point symbol of specific 3d marker style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMPointSymbol ConstructPointSymbol(Simple3DMarkerStyle style)
```
### ConstructPolygonSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol()
```
### ConstructPolygonSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color)
```
### ConstructPolygonSymbol(CIMColor, SimpleFillStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color and style.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleFillStyle fillStyle)
```
### ConstructPolygonSymbol(CIMColor, SimpleFillStyle, CIMStroke)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color, style and outline.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleFillStyle fillStyle, CIMStroke outline)
```
### ConstructPolygonSymbol(CIMColor, SimpleStipplePattern)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color and stipple pattern.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleStipplePattern stipplePattern)
```
### ConstructPolygonSymbol(CIMColor, SimpleStipplePattern, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol of specific color, fill color, and stipple pattern.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMColor color, SimpleStipplePattern stipplePattern, CIMColor fillColor)
```
### ConstructPolygonSymbol(CIMFill, CIMStroke)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol from a fill and an outline.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMFill fill, CIMStroke outline)
```
### ConstructPolygonSymbol(CIMFill, CIMStroke, CIMColor, SimpleStipplePattern)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol with a specific fill, stroke, and stipple pattern.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMFill fill, CIMStroke outline, CIMColor color, SimpleStipplePattern stipplePattern)
```
### ConstructPolygonSymbol(CIMFill, CIMStroke, CIMMarker)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol from a fill and an outline.</p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbol(CIMFill fill, CIMStroke outline, CIMMarker pointMarker)
```
### ConstructPolygonSymbolWithPenInkCrossHatch(CIMColor, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol in the specified color representing a pen and ink cross hatch effect.
See <a href="https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/" sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="2">https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/</a></p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbolWithPenInkCrossHatch(CIMColor color, bool includeBorder)
```
### ConstructPolygonSymbolWithPenInkRipple(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol in the specified color representing a pen and ink ripple water fill.
See <a href="https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/" sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="2">https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/</a></p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbolWithPenInkRipple(CIMColor color)
```
### ConstructPolygonSymbolWithPenInkStipple(CIMColor, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a polygon symbol in the specified color representing a pen and ink stipple effect.
See <a href="https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/" sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="2">https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/please-steal-this-pen-and-ink-style/</a></p>


```csharp
CIMPolygonSymbol ConstructPolygonSymbolWithPenInkStipple(CIMColor color, bool includeBorder)
```
### ConstructProceduralSymbol(string, FeatureLayer, IEnumerable&lt;CIMPrimitiveOverride&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Create a symbol reference with a procedural symbol layer for a rule package. This
method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMSymbolReference ConstructProceduralSymbol(string rulePackagePath, FeatureLayer featureLayer, IEnumerable<CIMPrimitiveOverride> overrides = null)
```
### ConstructSolidFill(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a solid fill of specific color.</p>


```csharp
CIMFill ConstructSolidFill(CIMColor color)
```
### ConstructStroke()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke.</p>


```csharp
CIMStroke ConstructStroke()
```
### ConstructStroke(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke of specific color.</p>


```csharp
CIMStroke ConstructStroke(CIMColor color)
```
### ConstructStroke(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke of specific color and width.</p>


```csharp
CIMStroke ConstructStroke(CIMColor color, double width)
```
### ConstructStroke(CIMColor, double, SimpleLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a stroke of specific color, width and style.</p>


```csharp
CIMStroke ConstructStroke(CIMColor color, double width, SimpleLineStyle lineStyle)
```
### ConstructStroke(CIMColor, double, SimpleLineStyle, Simple3DLineStyle)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D stroke of specific color, width and style.</p>


```csharp
CIMStroke ConstructStroke(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D)
```
### ConstructStroke(CIMColor, double, SimpleLineStyle, Simple3DLineStyle, Simple3DLineAnchor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a 3D stroke of specific color, width and style.</p>


```csharp
CIMStroke ConstructStroke(CIMColor color, double width, SimpleLineStyle lineStyle, Simple3DLineStyle lineStyle3D, Simple3DLineAnchor anchor3D)
```
### ConstructTextSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol()
```
### ConstructTextSymbol(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(CIMColor color)
```
### ConstructTextSymbol(CIMColor, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color and size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(CIMColor color, double size)
```
### ConstructTextSymbol(CIMColor, double, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color, size, and font family name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(CIMColor color, double size, string fontFamilyName)
```
### ConstructTextSymbol(CIMColor, double, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color, size, font family name and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(CIMColor color, double size, string fontFamilyName, string fontStyleName)
```
### ConstructTextSymbol(CIMPolygonSymbol, double, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its polygon symbol, size, and font family name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(CIMPolygonSymbol symbol, double size, string fontFamilyName)
```
### ConstructTextSymbol(CIMPolygonSymbol, double, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its polygon symbol, size, font family name and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(CIMPolygonSymbol symbol, double size, string fontFamilyName, string fontStyleName)
```
### ConstructTextSymbol(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its size. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(double size)
```
### ConstructTextSymbol(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its font family name. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(string fontFamilyName)
```
### ConstructTextSymbol(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a default text symbol given its color, size, font family name and style. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMTextSymbol ConstructTextSymbol(string fontFamilyName, string fontStyleName)
```
### ConstructWaterFill(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a water fill of specific color.</p>


```csharp
CIMFill ConstructWaterFill(CIMColor color)
```
### ConstructWaterFill(CIMColor, WaterbodySize, WaveStrength)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Constructs a water fill of specific color, waterbody size and wave strength.</p>


```csharp
CIMFill ConstructWaterFill(CIMColor color, WaterbodySize waterBodySize, WaveStrength waveStrength)
```
### DefaultFill

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default fill.</p>


```csharp
CIMFill DefaultFill { get; }
```
### DefaultFont

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default font name and style name.</p>


```csharp
(string fontName, string styleName) DefaultFont { get; }
```
### DefaultLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default line symbol.</p>


```csharp
CIMLineSymbol DefaultLineSymbol { get; }
```
### DefaultMarker

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default marker.</p>


```csharp
CIMMarker DefaultMarker { get; }
```
### DefaultMaterial

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default material.</p>


```csharp
CIMMaterialSymbolLayer DefaultMaterial { get; }
```
### DefaultMeshEdge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default CIMMeshEdge.</p>


```csharp
CIMMeshEdge DefaultMeshEdge { get; }
```
### DefaultMeshSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default mesh symbol.</p>


```csharp
CIMMeshSymbol DefaultMeshSymbol { get; }
```
### DefaultPointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default point symbol.</p>


```csharp
CIMPointSymbol DefaultPointSymbol { get; }
```
### DefaultPolygonSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default polygon symbol.</p>


```csharp
CIMPolygonSymbol DefaultPolygonSymbol { get; }
```
### DefaultSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default size.</p>


```csharp
double DefaultSize { get; }
```
### DefaultStroke

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default stroke.</p>


```csharp
CIMStroke DefaultStroke { get; }
```
### DefaultTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default text symbol.</p>


```csharp
CIMTextSymbol DefaultTextSymbol { get; }
```
### DefaultWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the default width.</p>


```csharp
double DefaultWidth { get; }
```
### GenerateImage(CIMPointSymbol, OutputImageFormat, double, bool, double, long, long, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Generates an image for point sybmols.</p>


```csharp
MemoryStream GenerateImage(CIMPointSymbol pointSymbol, OutputImageFormat imageFormat, double scaleFactor, bool centerAnchorPoint, double dpi, long width, long height, CIMColor backgroundColor)
```
### GetAvailableFonts()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Gets the list of available fonts.</p>


```csharp
IReadOnlyList<(string fontName, List<string> fontStyles)> GetAvailableFonts()
```
### GetDictionarySymbol(string, Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Builds a symbol from a dictionary. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMSymbol GetDictionarySymbol(string dictionaryName, Dictionary<string, object> values)
```
### GetRulePackageDescription(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Populate the associated rule package description. This method must be called on
the MCT. Use QueuedTask.Run.</p>


```csharp
RulePackageDescription GetRulePackageDescription(string rulePackagePath)
```
### IsFontAvailable(string, string, FontType, List&lt;CIMFontVariation&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Checks whether a specific font is available in the application for the Pro session.</p>


```csharp
bool IsFontAvailable(string fontName, string fontStyle, FontType fontType, List<CIMFontVariation> fontVariationSettings)
```
### LayerIsCompatibleWithRulePackage(string, FeatureLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Checks the compatibility of the rule package geometry with the feature layer shape type for use as a renderer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool LayerIsCompatibleWithRulePackage(string rulePackagePath, FeatureLayer featureLayer)
```
### ShapeTypeSupportedWithRulePackage(FeatureLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ISymbolFactory.yml" sourcestartlinenumber="1">Checks if the underlying shape type of the layer features is supported for use with rule package renderers.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool ShapeTypeSupportedWithRulePackage(FeatureLayer featureLayer)
```


