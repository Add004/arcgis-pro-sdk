# ElementFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Provides methods to create the different types of elements.</p>


## Object Signature

```csharp
public class ElementFactory : IElementFactory
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Elements can be created in an <xref href="ArcGIS.Desktop.Mapping.IElementContainer" data-throw-if-not-resolved="false"></xref> to
include Layouts, Graphics Layers, and Group Elements</p>


## Members

### CreateArrowGraphicElement(IElementContainer, Polyline, ArrowInfo, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create an arrow graphic based on the provided geometry and <xref href="ArcGIS.Desktop.Layouts.ArrowInfo" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreateArrowGraphicElement(IElementContainer elementContainer, Polyline arrowLine, ArrowInfo arrowInfo, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateElement(IElementContainer, CIMElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Creates an element using the corresponding <xref href="ArcGIS.Core.CIM.CIMElement" data-throw-if-not-resolved="false"></xref> definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Element CreateElement(IElementContainer elementContainer, CIMElement cimElement, bool select = true)
```
### CreateGraphicElement(IElementContainer, CIMGraphic, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref>
and element properties. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreateGraphicElement(IElementContainer elementContainer, CIMGraphic cimGraphic, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateGraphicElement(IElementContainer, Geometry, CIMSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input geometry
and associated symbol and properties (optional). This method must be
called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreateGraphicElement(IElementContainer elementContainer, Geometry geometry, CIMSymbol symbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateGraphicElements(IElementContainer, IEnumerable&lt;CIMGraphic&gt;, IEnumerable&lt;string&gt;, bool, IEnumerable&lt;ElementInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref> collection
and element properties. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public IList<GraphicElement> CreateGraphicElements(IElementContainer elementContainer, IEnumerable<CIMGraphic> cimGraphics, IEnumerable<string> elementNames = null, bool select = true, IEnumerable<ElementInfo> elementInfos = null)
```
### CreateGroupElement(IElementContainer, IEnumerable&lt;Element&gt;, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a group element from the input element collection and element
properties. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GroupElement CreateGroupElement(IElementContainer elementContainer, IEnumerable<Element> elements = null, string elementName = "", bool select = true, ElementInfo groupElementInfo = null)
```
### CreateMapFrameElement(IElementContainer, Geometry, Map, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a map frame element based on the input map frame polygon and map URI.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public MapFrame CreateMapFrameElement(IElementContainer elementContainer, Geometry frameOrLocation, Map map, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateMapSurroundElement(IElementContainer, Geometry, MapSurroundInfo, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a map surround element based on the geometry and associated
map surround and element properties.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public MapSurround CreateMapSurroundElement(IElementContainer elementContainer, Geometry frameOrLocation, MapSurroundInfo surroundInfo, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreatePictureGraphicElement(IElementContainer, Geometry, string, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Creates a picture graphic element based on the input geometry and symbol.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreatePictureGraphicElement(IElementContainer elementContainer, Geometry frameOrLocation, string url, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreatePredefinedShapeGraphicElement(IElementContainer, PredefinedShape, Envelope, CIMPolygonSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a polygon graphic of the specified <xref href="ArcGIS.Desktop.Layouts.PredefinedShape" data-throw-if-not-resolved="false"></xref> using
the provided location, optional size dimensions, and symbol. This method must be
called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreatePredefinedShapeGraphicElement(IElementContainer elementContainer, PredefinedShape shapeType, Envelope bounds, CIMPolygonSymbol polySymbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreatePredefinedShapeGraphicElement(IElementContainer, PredefinedShape, MapPoint, double, double, CIMPolygonSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Create a polygon graphic of the specified <xref href="ArcGIS.Desktop.Layouts.PredefinedShape" data-throw-if-not-resolved="false"></xref> using
the provided location, optional size dimensions, and symbol. This method must be
called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreatePredefinedShapeGraphicElement(IElementContainer elementContainer, PredefinedShape shapeType, MapPoint location, double width = 0, double height = 0, CIMPolygonSymbol polySymbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateTextGraphicElement(IElementContainer, TextType, Geometry, CIMTextSymbol, string, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Creates a text graphic element based on the input geometry, symbol, text and
other optional parameters. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GraphicElement CreateTextGraphicElement(IElementContainer elementContainer, TextType textType, Geometry geometry, CIMTextSymbol textSymbol = null, string text = "", string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementFactory.yml" sourcestartlinenumber="1">Provides access to helper functions that create layout elements.</p>


```csharp
public static IElementFactory Instance { get; }
```


