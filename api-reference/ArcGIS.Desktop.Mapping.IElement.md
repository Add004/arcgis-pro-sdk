# IElement

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Element interface that works on layout or map graphic layers.</p>


## Object Signature

```csharp
public interface IElement
```


## Members

### CanConvertToGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets whether the given element can be converted to graphics.</p>


```csharp
bool CanConvertToGraphics { get; }
```
### ConvertToGraphics()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Convert the element to graphics.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
IList<IElement> ConvertToGraphics()
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the Custom Properties for the element.</p>


```csharp
IList<CIMStringMap> CustomProperties { get; }
```
### GetAnchor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the anchor position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Anchor GetAnchor()
```
### GetAnchorPoint()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Get the element anchor point location.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Coordinate2D GetAnchorPoint()
```
### GetBounds(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the bounding box for the element.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Envelope GetBounds(bool rotated = false)
```
### GetCustomProperty(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets a Custom Property value for the element.</p>


```csharp
string GetCustomProperty(string key)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Returns the element's CIM definition.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
CIMElement GetDefinition()
```
### GetGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> which is a CIM representation of the GraphicElement shape.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Geometry GetGeometry()
```
### GetHeight()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the height of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
double GetHeight()
```
### GetLockedAspectRatio()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the locked aspect ratio value of the element. If This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
bool GetLockedAspectRatio()
```
### GetParent(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the parent of this element.</p>


```csharp
IElementContainer GetParent(bool topMost = false)
```
### GetRotation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the rotation value for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
double GetRotation()
```
### GetWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the width of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
double GetWidth()
```
### GetX()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the X position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
double GetX()
```
### GetY()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the Y position of the element. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
double GetY()
```
### IsExpandedInTOC

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets or sets if a group element is expanded in the contents pane.</p>


```csharp
bool IsExpandedInTOC { get; set; }
```
### IsLocked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the locked state of an element.</p>


```csharp
bool IsLocked { get; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the visibility of an element.</p>


```csharp
bool IsVisible { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the name of the element.</p>


```csharp
string Name { get; }
```
### Parent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the parent of this element.</p>


```csharp
IElementContainer Parent { get; }
```
### SetAnchor(Anchor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the anchor position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetAnchor(Anchor anchor)
```
### SetAnchorPoint(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the element anchor point to the X and Y location specified.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetAnchorPoint(Coordinate2D anchorPoint)
```
### SetCustomProperties(IEnumerable&lt;CIMStringMap&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets multiple CustomProperty values for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetCustomProperties(IEnumerable<CIMStringMap> customProperties)
```
### SetCustomProperty(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets a CustomProperty value for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetCustomProperty(string key, string value)
```
### SetCustomProperty(string[], string[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets multiple CustomProperty values for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetCustomProperty(string[] keys, string[] values)
```
### SetDefinition(CIMElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMElement?text=CIMElement" data-throw-if-not-resolved="false"></xref> back to the element on the page layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetDefinition(CIMElement cimElement)
```
### SetGeometry(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Applies the changes made to a <xref href="ArcGIS.Core.CIM.CIMGraphic?text=CIMGraphic" data-throw-if-not-resolved="false"></xref> back to the GraphicElement. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetGeometry(Geometry geometry)
```
### SetHeight(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the height of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetHeight(double height)
```
### SetLocked(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the locked state of an element on a page layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetLocked(bool isLocked)
```
### SetLockedAspectRatio(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the locked aspect ratio value of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetLockedAspectRatio(bool lockedAspectRatio)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the name of the element.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetName(string name)
```
### SetRotation(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the rotation value for the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetRotation(double rotation)
```
### SetTOCPositionAbsolute(IElementContainer, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the position of an element either at the top or bottom of the layout TOC or a group element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetTOCPositionAbsolute(IElementContainer targetContainer, bool isTop)
```
### SetTOCPositionRelative(IElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the position of an element either above or below a reference element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetTOCPositionRelative(IElement targetElement, bool isAbove)
```
### SetVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the visibility of an element on a page layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetVisible(bool isVisible)
```
### SetWidth(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the width of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetWidth(double width)
```
### SetX(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the X position of the element. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetX(double x)
```
### SetY(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Sets the Y position of the element. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
void SetY(double y)
```
### ZOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElement.yml" sourcestartlinenumber="1">Gets the Z order of the element relative to its parent</p>


```csharp
int ZOrder { get; }
```


