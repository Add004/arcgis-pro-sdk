# GraphicFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Provides a mechanism for creating <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref>. The
CIMGraphic is typically used to create a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class GraphicFactory : IGraphicFactory
```


## Members

### CreateArrowGraphic(Polyline, ArrowInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Create an arrow graphic based on the provided geometry and <xref href="ArcGIS.Desktop.Layouts.ArrowInfo" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMGraphic CreateArrowGraphic(Polyline arrowLine, ArrowInfo arrowInfo)
```
### CreateLegendPatchGraphic(PatchShape, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Create a polygon or line graphic of the specified <xref href="ArcGIS.Core.CIM.PatchShape" data-throw-if-not-resolved="false"></xref> using the
provided extent. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMGraphic CreateLegendPatchGraphic(PatchShape patchShape, Envelope extent)
```
### CreateLegendPatchGraphic(PatchShape, Envelope, CIMSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Create a polygon or line graphic of the specified <xref href="ArcGIS.Core.CIM.PatchShape" data-throw-if-not-resolved="false"></xref> using the
provided extent and symbol. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMGraphic CreateLegendPatchGraphic(PatchShape patchShape, Envelope extent, CIMSymbol patchSymbol)
```
### CreatePictureGraphic(Geometry, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Creates a picture graphic element based on the input geometry and symbol.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMPictureGraphic CreatePictureGraphic(Geometry frameOrLocation, string url)
```
### CreatePredefinedShapeGraphic(PredefinedShape, Envelope, CIMPolygonSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Create a polygon graphic of the specified <xref href="ArcGIS.Desktop.Layouts.PredefinedShape" data-throw-if-not-resolved="false"></xref> using the
provided bounds and symbol. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPolygonGraphic CreatePredefinedShapeGraphic(PredefinedShape shapeType, Envelope bounds, CIMPolygonSymbol polySymbol = null)
```
### CreatePredefinedShapeGraphic(PredefinedShape, MapPoint, double, double, CIMPolygonSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Create a polygon graphic of the specified <xref href="ArcGIS.Desktop.Layouts.PredefinedShape" data-throw-if-not-resolved="false"></xref> using
the provided extent and size dimension(s), and symbol. This method must be called
on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMPolygonGraphic CreatePredefinedShapeGraphic(PredefinedShape shapeType, MapPoint location, double width, double height = 0, CIMPolygonSymbol polySymbol = null)
```
### CreateSimpleGraphic(Geometry, CIMSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Creates a point, line, polygon or text graphic based on the input geometry and symbol.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMGraphic CreateSimpleGraphic(Geometry geometry, CIMSymbol symbol = null)
```
### CreateSimpleTextGraphic(TextType, Geometry, CIMTextSymbol, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Creates a text graphic based on the input geometry, symbol, and text.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMTextGraphicBase CreateSimpleTextGraphic(TextType textType, Geometry geometry, CIMTextSymbol textSymbol = null, string text = "")
```
### GetGeometry(CIMGraphic)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Get the underlying geometry from the <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref></p>


```csharp
public Geometry GetGeometry(CIMGraphic graphic)
```
### GetGraphicOutline(IElementContainer, CIMGraphic)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Get the outline geometry for the input CIMGraphic. This method must
be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Geometry GetGraphicOutline(IElementContainer container, CIMGraphic graphic)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicFactory.yml" sourcestartlinenumber="1">Provides access to helper functions that create <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static IGraphicFactory Instance { get; }
```


