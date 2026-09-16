# GraphicsLayerExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Extension methods for <xref href="ArcGIS.Desktop.Mapping.GraphicsLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public static class GraphicsLayerExtensions
```


## Members

### AddElement(GraphicsLayer, CIMGraphic, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Add a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT.Use QueuedTask.Run.</p>


```csharp
public static GraphicElement AddElement(this GraphicsLayer graphicsLayer, CIMGraphic cimGraphic, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### AddElement(GraphicsLayer, Geometry, CIMSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Add a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input geometry and symbol (optional).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static GraphicElement AddElement(this GraphicsLayer graphicsLayer, Geometry geometry, CIMSymbol symbol = null, string elementName = "", bool select = false, ElementInfo elementInfo = null)
```
### AddElement(GraphicsLayer, MapPoint, string, CIMTextSymbol, string, bool, ElementInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Add a <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the input point, text, and textsymbol (optional).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static GraphicElement AddElement(this GraphicsLayer graphicsLayer, MapPoint point, string text, CIMTextSymbol textSymbol = null, string elementName = "", bool select = true, ElementInfo elementInfo = null)
```
### AddElements(GraphicsLayer, IEnumerable&lt;CIMGraphic&gt;, IEnumerable&lt;string&gt;, bool, IEnumerable&lt;ElementInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Add a collection of <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> based on the list of <xref href="ArcGIS.Core.CIM.CIMGraphic" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<GraphicElement> AddElements(this GraphicsLayer graphicsLayer, IEnumerable<CIMGraphic> graphics, IEnumerable<string> elementNames = null, bool select = false, IEnumerable<ElementInfo> elementInfos = null)
```
### BringForward(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Bring the element forward within its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void BringForward(this GraphicsLayer graphicsLayer, Element element)
```
### BringForward(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Bring the elements forward within their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void BringForward(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### BringToFront(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Bring the element to the front of its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void BringToFront(this GraphicsLayer graphicsLayer, Element element)
```
### BringToFront(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Bring the elements to the front of their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void BringToFront(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### CanBringForward(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Checks whether the given element can be moved forward within its parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanBringForward(this GraphicsLayer graphicsLayer, Element element)
```
### CanBringForward(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Checks whether the given elements can be moved forward within their parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanBringForward(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### CanSendBackward(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Checks whether the given element can be moved back within its parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanSendBackward(this GraphicsLayer graphicsLayer, Element element)
```
### CanSendBackward(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Checks whether the given elements can be moved back within their parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static bool CanSendBackward(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### ClearSelection(GraphicsLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Clears the current element selection within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ClearSelection(this GraphicsLayer graphicsLayer)
```
### CopyElements(GraphicsLayer, GroupElement, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Copy the elements into a group element within the graphics layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Element> CopyElements(this GraphicsLayer graphicsLayer, GroupElement group, IEnumerable<Element> elements)
```
### CopyElements(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Copy the elements into the graphics layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Element> CopyElements(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### FindElement(GraphicsLayer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Finds the element recursively with the given name within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Element FindElement(this GraphicsLayer graphicsLayer, string elementName)
```
### FindElements(GraphicsLayer, IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Finds the elements recursively with the given names within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IList<Element> FindElements(this GraphicsLayer graphicsLayer, IEnumerable<string> elementNames)
```
### GetElements(GraphicsLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Get the collection of elements from the <xref href="ArcGIS.Desktop.Mapping.GraphicsLayer" data-throw-if-not-resolved="false"></xref>. Nesting
within <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref><b>is</b> preserved.</p>


```csharp
public static IReadOnlyList<Element> GetElements(this GraphicsLayer graphicsLayer)
```
### GetElementsAsFlattenedList(GraphicsLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Get the collection of <xref href="ArcGIS.Desktop.Layouts.GraphicElement" data-throw-if-not-resolved="false"></xref> from the <xref href="ArcGIS.Desktop.Mapping.GraphicsLayer" data-throw-if-not-resolved="false"></xref>.
Nested groups within <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref> are <b>not</b> preserved.</p>


```csharp
public static IReadOnlyList<GraphicElement> GetElementsAsFlattenedList(this GraphicsLayer graphicsLayer)
```
### GetSelectedElements(GraphicsLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Gets the currently selected elements within the GraphicsLayer collection.</p>


```csharp
public static IReadOnlyList<Element> GetSelectedElements(this GraphicsLayer graphicsLayer)
```
### GroupElements(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Group the collection of elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static GroupElement GroupElements(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### RemoveElement(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Remove the element from the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void RemoveElement(this GraphicsLayer graphicsLayer, Element element)
```
### RemoveElements(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Remove the elements from the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void RemoveElements(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements = null)
```
### SelectElement(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Select the element within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SelectElement(this GraphicsLayer graphicsLayer, Element element)
```
### SelectElements(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Select the elements within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SelectElements(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements = null)
```
### SendBackward(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Send the element backward within its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SendBackward(this GraphicsLayer graphicsLayer, Element element)
```
### SendBackward(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Send the elements backward within their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SendBackward(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### SendToBack(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Send the element to the back of its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SendToBack(this GraphicsLayer graphicsLayer, Element element)
```
### SendToBack(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Send the elements to the back of their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SendToBack(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements)
```
### UnGroupElement(GraphicsLayer, GroupElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Ungroup the elements contained in 'group'.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UnGroupElement(this GraphicsLayer graphicsLayer, GroupElement group)
```
### UnGroupElements(GraphicsLayer, IEnumerable&lt;GroupElement&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Ungroup the elements contained in 'groups'.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UnGroupElements(this GraphicsLayer graphicsLayer, IEnumerable<GroupElement> groups)
```
### UnSelectElement(GraphicsLayer, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Unselect the element within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UnSelectElement(this GraphicsLayer graphicsLayer, Element element)
```
### UnSelectElements(GraphicsLayer, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayerExtensions.yml" sourcestartlinenumber="1">Unselect the elements within the GraphicsLayer collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void UnSelectElements(this GraphicsLayer graphicsLayer, IEnumerable<Element> elements = null)
```


