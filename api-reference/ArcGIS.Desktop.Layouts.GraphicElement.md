# GraphicElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Represents a graphic element on a page layout.</p>


## Object Signature

```csharp
public class GraphicElement : Element, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable
```

## Remarks

<p>
    Graphic elements are a type of <xref href="ArcGIS.Desktop.Layouts.Element?text=Element" data-throw-if-not-resolved="false"></xref> and include inserted graphic points, lines, or area shapes.
    <xref href="ArcGIS.Desktop.Layouts.PictureElement?text=PictureElement" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Layouts.TextElement?text=TextElement" data-throw-if-not-resolved="false"></xref> are 
    also a type of graphic element.
    </p>
<p>
    The <xref href="ArcGIS.Desktop.Layouts.GraphicElement.Graphic?text=Graphic" data-throw-if-not-resolved="false"></xref> property returns a CIM representation of the graphic specific attributes 
    for a GraphicElement. This may provide additional, finer grained properties exposed in the CIM that are not exposed in the managed API. 
    <xref href="ArcGIS.Desktop.Layouts.GraphicElement.SetGraphic?text=SetGraphic" data-throw-if-not-resolved="false"></xref> applies the changes made to a modified 
    <xref href="ArcGIS.Core.CIM.CIMGraphic?text=CIMGraphic" data-throw-if-not-resolved="false"></xref> back to the GraphicElement.
    </p>
<p>
    The <xref href="ArcGIS.Desktop.Layouts.GraphicElement.Clone?text=Clone" data-throw-if-not-resolved="false"></xref> method allows you to duplicate existing graphic elements on your page layout. 
    This can be useful where you may have a variable number of pictures, for example, on each page in the map series.  Rather than authoring a layout with 
    all possibilities, a single picture element can be cloned and updated the appropriate number of times to reference a different set of pictures on disk 
    for each page in the series.
    </p>


## Members

### ApplyStyle(StyleItem, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Apply the given style to the element. Retain the current symbol size
for Point, Line, Polygon, and Text elements. This method must be called
on the MCT.  Use QueuedTask.Run</p>


```csharp
public virtual void ApplyStyle(StyleItem styleItem, bool keepSymbolSize)
```
### CanApplyStyle(StyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Gets whether the StyleItem can be applied</p>


```csharp
public override bool CanApplyStyle(StyleItem styleItem)
```
### CanSupportCornerRounding

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Gets whether the Graphic Element can support corner rounding or not</p>


```csharp
public bool CanSupportCornerRounding { get; }
```
### Clone(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Generates a cloned copy of an existing GraphicElement on a page layout.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public GraphicElement Clone(string suffix = "")
```
### CornerRounding

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Gets the corner rounding</p>


```csharp
public double CornerRounding { get; }
```
### GetGraphic()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.CIM.CIMGraphic?text=CIMGraphic" data-throw-if-not-resolved="false"></xref> which is a CIM representation of the graphic specific attributes for a GraphicElement.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMGraphic GetGraphic()
```
### SetCornerRounding(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Set corner rounding. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetCornerRounding(double cornerRounding)
```
### SetGraphic(CIMGraphic)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GraphicElement.yml" sourcestartlinenumber="1">Applies the changes made to a <xref href="ArcGIS.Core.CIM.CIMGraphic?text=CIMGraphic" data-throw-if-not-resolved="false"></xref> back to the GraphicElement. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetGraphic(CIMGraphic cimGraphic)
```


