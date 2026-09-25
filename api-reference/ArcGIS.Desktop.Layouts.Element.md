# Element

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Represents an abstract page layout element.</p>


## Object Signature

```csharp
public abstract class Element : PropertyChangedBase, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">There are many types of elements.  This class exposes members that are common to all layout elements.</p>


## Members

### ApplyStyle(StyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Apply the given style to the element.
This method must be called on the MCT.  Use QueuedTask.Run</p>


```csharp
public virtual void ApplyStyle(StyleItem styleItem)
```
### CanApplyStyle(StyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets whether the StyleItem can be applied</p>


```csharp
public virtual bool CanApplyStyle(StyleItem styleItem)
```
### CanConvertToGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets whether the given element can be converted to graphics</p>


```csharp
public bool CanConvertToGraphics { get; }
```
### CompareTo(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Compare Elements by name.</p>


```csharp
public int CompareTo(object o)
```
### ConvertToGraphics()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Convert the element to graphics.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IList<IElement> ConvertToGraphics()
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the Custom Properties for the element.</p>


```csharp
public IList<CIMStringMap> CustomProperties { get; }
```
### DoesFitFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets whether the element fits the frame.</p>


```csharp
public bool DoesFitFrame { get; }
```
### Equals(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Evaluates whether the elements are equal based on <xref href="ArcGIS.Desktop.Layouts.Element.Name" data-throw-if-not-resolved="false"></xref></p>


```csharp
public bool Equals(Element other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Determines whether the specified element is equivalent to the current element.</p>


```csharp
public override bool Equals(object obj)
```
### GetAnchor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the anchor position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Anchor GetAnchor()
```
### GetAnchorPoint()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Get the element anchor point location.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual Coordinate2D GetAnchorPoint()
```
### GetBounds(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the bounding box for the element.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual Envelope GetBounds(bool rotated = false)
```
### GetCustomProperty(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets a Custom Property value for the element.</p>


```csharp
public string GetCustomProperty(string key)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Returns the element's CIM definition.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual CIMElement GetDefinition()
```
### GetGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> which is a CIM representation of the GraphicElement shape.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual Geometry GetGeometry()
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Serves as the default hash function.</p>


```csharp
public override int GetHashCode()
```
### GetHeight()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the height of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual double GetHeight()
```
### GetLockedAspectRatio()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the locked aspect ratio value of the element. If This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool GetLockedAspectRatio()
```
### GetParent(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the parent of this element.</p>


```csharp
public IElementContainer GetParent(bool topMost = false)
```
### GetRotation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the rotation value for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public double GetRotation()
```
### GetWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the width of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual double GetWidth()
```
### GetX()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the X position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual double GetX()
```
### GetY()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the Y position of the element. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual double GetY()
```
### IsDecorative

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets whether the element is decorative in an accessible PDF.</p>


```csharp
public bool IsDecorative { get; }
```
### IsExpandedInTOC

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets or sets if a group element is expanded in the contents pane.</p>


```csharp
public bool IsExpandedInTOC { get; set; }
```
### IsLocked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the locked state of an element.</p>


```csharp
public virtual bool IsLocked { get; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the visibility of an element.</p>


```csharp
public bool IsVisible { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the name of the element.</p>


```csharp
public string Name { get; }
```
### SetAnchor(Anchor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the anchor position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetAnchor(Anchor anchor)
```
### SetAnchorPoint(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the element anchor point to the X and Y location specified.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void SetAnchorPoint(Coordinate2D anchorPoint)
```
### SetCustomProperties(IEnumerable&lt;CIMStringMap&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets multiple CustomProperty values for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetCustomProperties(IEnumerable<CIMStringMap> customProperties)
```
### SetCustomProperty(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets a CustomProperty value for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetCustomProperty(string key, string value)
```
### SetCustomProperty(string[], string[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets multiple CustomProperty values for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetCustomProperty(string[] keys, string[] values)
```
### SetDecorative(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets whether the element is decorative in an accessible PDF. Decorative elements are not read by assistive technologies.
This setting will be ignored for elements that do not support the decorative flag. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetDecorative(bool isDecorative)
```
### SetDefinition(CIMElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMElement?text=CIMElement" data-throw-if-not-resolved="false"></xref> back to the element on the page layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void SetDefinition(CIMElement cimElement)
```
### SetGeometry(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Applies the changes made to a <xref href="ArcGIS.Core.CIM.CIMGraphic?text=CIMGraphic" data-throw-if-not-resolved="false"></xref> back to the GraphicElement. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void SetGeometry(Geometry geometry)
```
### SetHeight(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the height of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void SetHeight(double height)
```
### SetLocked(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the locked state of an element on a page layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetLocked(bool isLocked)
```
### SetLockedAspectRatio(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the locked aspect ratio value of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetLockedAspectRatio(bool lockedAspectRatio)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the name of the element.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetRotation(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the rotation value for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetRotation(double rotation)
```
### SetTOCPositionAbsolute(IElementContainer, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the position of an element either at the top or bottom of the layout TOC or a group element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetTOCPositionAbsolute(IElementContainer targetContainer, bool isTop)
```
### SetTOCPositionRelative(Element, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the position of an element either above or below a reference element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetTOCPositionRelative(Element targetElement, bool isAbove)
```
### SetTOCPositionRelative(IElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the position of an element either above or below a reference element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetTOCPositionRelative(IElement targetElement, bool isAbove)
```
### SetVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the visibility of an element on a page layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetVisible(bool isVisible)
```
### SetWidth(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the width of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void SetWidth(double width)
```
### SetX(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the X position of the element. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual void SetX(double x)
```
### SetY(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Sets the Y position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual void SetY(double y)
```
### ZOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Element.yml" sourcestartlinenumber="1">Gets the Z order of the element relative to its parent</p>


```csharp
public int ZOrder { get; }
```


