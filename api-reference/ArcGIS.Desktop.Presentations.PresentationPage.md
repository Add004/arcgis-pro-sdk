# PresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Represents a presentation page.</p>


## Object Signature

```csharp
public class PresentationPage : PropertyChangedBase, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```


## Members

### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the background color of a presentation page.</p>


```csharp
public CIMColor BackgroundColor { get; }
```
### BringForward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Bring the element forward within its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringForward(Element element)
```
### BringForward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Bring the elements forward within their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringForward(IEnumerable<Element> elements)
```
### BringToFront(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Bring the element to the front of its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringToFront(Element element)
```
### BringToFront(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Bring the elements to the front of their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringToFront(IEnumerable<Element> elements)
```
### CanBringForward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Checks whether the given element can be moved forward within its parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanBringForward(Element element)
```
### CanBringForward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Checks whether the given elements can be moved forward within their parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanBringForward(IEnumerable<Element> elements)
```
### CanSendBackward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Checks whether the given element can be moved back within its parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSendBackward(Element element)
```
### CanSendBackward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Checks whether the given elements can be moved back within their parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSendBackward(IEnumerable<Element> elements)
```
### CopyElements(GroupElement, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Copy the elements into a group element within the presentation page.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Element> CopyElements(GroupElement group, IEnumerable<Element> elements)
```
### CopyElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Copy the elements into the presentation page.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Element> CopyElements(IEnumerable<Element> elements)
```
### DeleteElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Deletes an element from a presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteElement(Element element)
```
### DeleteElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Deletes the elements from a presentation page.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteElements(IEnumerable<Element> elements = null)
```
### DeleteElements(Func&lt;Element, bool&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Deletes an array of elements from a presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteElements(Func<Element, bool> predicate)
```
### FindElement(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Finds the element specified by name in the presentation page.</p>


```csharp
public Element FindElement(string elementName)
```
### FindElements(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Finds the elements recursively with the given names in the presentation page.</p>


```csharp
public IReadOnlyList<Element> FindElements(IEnumerable<string> elementNames)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Returns the presentation page's CIM definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPresentationPage GetDefinition()
```
### GetElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the collection of elements from the presentation page. Nesting within <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref> is preserved.</p>


```csharp
public IReadOnlyList<Element> GetElements()
```
### GetFlattenedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the flattened collection of elements in the container.</p>


```csharp
public IReadOnlyList<Element> GetFlattenedElements()
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the collection of currently selected presentation elements.</p>


```csharp
public IReadOnlyList<Element> GetSelectedElements()
```
### GroupElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Group the collection of elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GroupElement GroupElements(IEnumerable<Element> elements)
```
### HoldTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the page hold time in seconds.</p>


```csharp
public double HoldTime { get; }
```
### IsAutomaticAdvancement

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets whether automatic advancement to the next page is enabled.</p>


```csharp
public bool IsAutomaticAdvancement { get; }
```
### IsLocked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the locked state of a presentation page.</p>


```csharp
public bool IsLocked { get; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the visibility of a presentation page.</p>


```csharp
public bool IsVisible { get; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the margins of the background for a presentation page.</p>


```csharp
public CIMMargin Margin { get; }
```
### PageType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the page type.</p>


```csharp
public PresentationPageType PageType { get; }
```
### PresentationURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the path to the presentation in the project.</p>


```csharp
public string PresentationURI { get; }
```
### SelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Select the element within the presentation page.</p>


```csharp
public void SelectElement(Element element)
```
### SelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Set the selected elements for the presentation page.</p>


```csharp
public void SelectElements(IEnumerable<Element> elements)
```
### SendBackward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Send the element backward within its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendBackward(Element element)
```
### SendBackward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Send the elements backward within their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendBackward(IEnumerable<Element> elements)
```
### SendToBack(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Send the element to the back of its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendToBack(Element element)
```
### SendToBack(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Send the elements to the back of their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendToBack(IEnumerable<Element> elements)
```
### SetAutomaticAdvancement(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets whether automatic advancement to the next page is enabled. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetAutomaticAdvancement(bool isAutomaticAdvancement)
```
### SetBackgroundColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets the background color of a presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetBackgroundColor(CIMColor backgroundColor)
```
### SetDefinition(CIMPresentationPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMPresentationPage" data-throw-if-not-resolved="false"></xref> to the presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMPresentationPage cimPresentationPage)
```
### SetHoldTime(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets the page hold time. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetHoldTime(double holdTime)
```
### SetIsLocked(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets the locked state of a presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsLocked(bool isLocked)
```
### SetIsVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets the visibility of a presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsVisible(bool visible)
```
### SetMargin(CIMMargin)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets the margins of the background for a presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMargin(CIMMargin margin)
```
### SetTransition(CIMPresentationTransition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Sets the page transition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetTransition(CIMPresentationTransition transition)
```
### Transition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Gets the transition for a presentation page.</p>


```csharp
public CIMPresentationTransition Transition { get; }
```
### UnGroupElement(GroupElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Ungroup the elements contained in 'group'.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnGroupElement(GroupElement group)
```
### UnGroupElements(IEnumerable&lt;GroupElement&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Ungroup the elements contained in 'groups'.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnGroupElements(IEnumerable<GroupElement> groups)
```
### UnSelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Unselect the element on the presentation page.</p>


```csharp
public void UnSelectElement(Element element)
```
### UnSelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPage.yml" sourcestartlinenumber="1">Unselect the elements on the presentation page.</p>


```csharp
public void UnSelectElements(IEnumerable<Element> elements = null)
```


