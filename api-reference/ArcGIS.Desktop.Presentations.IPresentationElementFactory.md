# IPresentationElementFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Provides method signatures for creating the different types of elements in a presentation page.</p>


## Object Signature

```csharp
public interface IPresentationElementFactory
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Elements can be created in a <xref href="ArcGIS.Desktop.Presentations.PresentationPage" data-throw-if-not-resolved="false"></xref></p>


## Members

### CreateArrowGraphicElement(IElementContainer, Polyline, ArrowInfo, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates an arrow graphic based on the provided geometry and <xref href="ArcGIS.Desktop.Layouts.ArrowInfo" data-throw-if-not-resolved="false"></xref></p>


```csharp
GraphicElement CreateArrowGraphicElement(IElementContainer elementContainer, Polyline arrowLine, ArrowInfo arrowInfo, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateElement(IElementContainer, CIMElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates an element using the corresponding <xref href="ArcGIS.Core.CIM.CIMElement" data-throw-if-not-resolved="false"></xref> definition.</p>


```csharp
Element CreateElement(IElementContainer elementContainer, CIMElement cimElement, bool select = true)
```
### CreateGraphicElement(IElementContainer, CIMGraphic, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Create a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref>
and element properties.</p>


```csharp
GraphicElement CreateGraphicElement(IElementContainer elementContainer, CIMGraphic cimGraphic, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateGraphicElement(IElementContainer, Geometry, CIMSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input geometry
and associated symbol and properties (optional).</p>


```csharp
GraphicElement CreateGraphicElement(IElementContainer elementContainer, Geometry geometry, CIMSymbol symbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateGraphicElements(IElementContainer, IEnumerable&lt;CIMGraphic&gt;, IEnumerable&lt;string&gt;, bool, IEnumerable&lt;ElementInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref> collection
and element properties.</p>


```csharp
IList<GraphicElement> CreateGraphicElements(IElementContainer elementContainer, IEnumerable<CIMGraphic> cimGraphics, IEnumerable<string> elementNames = null, bool select = true, IEnumerable<ElementInfo> elementInfos = null)
```
### CreateGroupElement(IElementContainer, IEnumerable&lt;Element&gt;, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates a group element from the input element collection and element
properties.</p>


```csharp
GroupElement CreateGroupElement(IElementContainer elementContainer, IEnumerable<Element> elements = null, string elementName = "", bool select = true, ElementInfo groupElementInfo = null)
```
### CreatePictureGraphicElement(IElementContainer, Geometry, string, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates a picture graphic element based on the input geometry and symbol.</p>


```csharp
GraphicElement CreatePictureGraphicElement(IElementContainer elementContainer, Geometry frameOrLocation, string url, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreatePredefinedShapeGraphicElement(IElementContainer, PredefinedShape, Envelope, CIMPolygonSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates a polygon graphic of the specified <xref href="ArcGIS.Desktop.Layouts.PredefinedShape" data-throw-if-not-resolved="false"></xref> using
the provided location, optional size dimensions, and symbol.</p>


```csharp
GraphicElement CreatePredefinedShapeGraphicElement(IElementContainer elementContainer, PredefinedShape shapeType, Envelope bounds, CIMPolygonSymbol polySymbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreatePredefinedShapeGraphicElement(IElementContainer, PredefinedShape, MapPoint, double, double, CIMPolygonSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates a polygon graphic of the specified <xref href="ArcGIS.Desktop.Layouts.PredefinedShape" data-throw-if-not-resolved="false"></xref> using
the provided location, optional size dimensions, and symbol.</p>


```csharp
GraphicElement CreatePredefinedShapeGraphicElement(IElementContainer elementContainer, PredefinedShape shapeType, MapPoint location, double width = 0, double height = 0, CIMPolygonSymbol polySymbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### CreateTextGraphicElement(IElementContainer, TextType, Geometry, CIMTextSymbol, string, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationElementFactory.yml" sourcestartlinenumber="1">Creates a text graphic based on the input geometry, symbol, text and
other optional parameters.</p>


```csharp
GraphicElement CreateTextGraphicElement(IElementContainer elementContainer, TextType textType, Geometry geometry, CIMTextSymbol textSymbol = null, string text = "", string elementName = "", bool select = true, ElementInfo elementInfo = null)
```


