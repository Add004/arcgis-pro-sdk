# Layout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Represents a page layout in a project and provides access to basic layout properties, including page information, access to elements, and export methods.</p>


## Object Signature

```csharp
public sealed class Layout : PropertyChangedBase, IElementContainer, IMetadataInfo, IElementContainerInternal, ISuspendableObservableCollection, IDisposable
```

## Remarks

<p>
    The Layout class provides access to all elements on a page layout.  Use <xref href="ArcGIS.Desktop.Layouts.Layout.FindElement?text=FindElement" data-throw-if-not-resolved="false"></xref> to reference 
    an individual element on page layout.  It is the best method to use because it also finds elements that are in group or nested group elements whereas a standard 
    c# method used with <xref href="ArcGIS.Desktop.Layouts.Layout.Elements?text=Elements" data-throw-if-not-resolved="false"></xref> will only find non-grouped elements.
    </p>
<p>
    The size and positioning of a page layout can be modified.  First use the <xref href="ArcGIS.Desktop.Layouts.Layout.GetPage?text=GetPage" data-throw-if-not-resolved="false"></xref> property to retrieve 
    the <xref href="ArcGIS.Core.CIM.CIMPage?text=CIMPage" data-throw-if-not-resolved="false"></xref>, modify the page properties, and then use <xref href="ArcGIS.Desktop.Layouts.Layout.SetPage?text=SetPage" data-throw-if-not-resolved="false"></xref> 
    to the apply the changes back to the layout.
    </p>


## Members

### BringForward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Bring the element forward within its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringForward(Element element)
```
### BringForward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Bring the elements forward within their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringForward(IEnumerable<Element> elements)
```
### BringToFront(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Bring the element to the front of its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringToFront(Element element)
```
### BringToFront(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Bring the elements to the front of their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BringToFront(IEnumerable<Element> elements)
```
### CanBringForward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Checks whether the given element can be moved forward within its parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanBringForward(Element element)
```
### CanBringForward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Checks whether the given elements can be moved forward within their parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanBringForward(IEnumerable<Element> elements)
```
### CanSendBackward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Checks whether the given element can be moved back within its parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSendBackward(Element element)
```
### CanSendBackward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Checks whether the given elements can be moved back within their parent's
element collection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSendBackward(IEnumerable<Element> elements)
```
### ClearElementSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Clear all selected elements in the page layout.</p>


```csharp
public void ClearElementSelection()
```
### CopyElements(GroupElement, IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Copy the elements into a group element within the page layout.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Element> CopyElements(GroupElement group, IEnumerable<Element> elements)
```
### CopyElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Copy the elements into the page layout.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Element> CopyElements(IEnumerable<Element> elements)
```
### DeleteElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Deletes an element on a page layout.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void DeleteElement(Element element)
```
### DeleteElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Deletes the elements from a page layout.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteElements(IEnumerable<Element> elements = null)
```
### DeleteElements(Func&lt;Element, bool&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Deletes an array of elements on a page layout.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void DeleteElements(Func<Element, bool> predicate)
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Object dispose</p>


```csharp
public void Dispose()
```
### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the collection of elements in a GroupElement.</p>


```csharp
public ReadOnlyObservableCollection<Element> Elements { get; }
```
### Export(ExportFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Export a layout to a variety of formats. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat)
```
### Export(ExportFormat, MapSeriesExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Export pages from a layout's associated map series using a specialized collection of settings. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat, MapSeriesExportOptions mapSeriesExportOptions)
```
### FindElement(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Finds an element with the given name on the page layout.</p>


```csharp
public Element FindElement(string name)
```
### FindElements(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Finds the elements recursively with the given names on the page layout.</p>


```csharp
public IList<Element> FindElements(IEnumerable<string> elementNames)
```
### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets whether the Layout metadata can be edited or not.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanEditMetadata()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Returns the element's CIM definition.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMLayout GetDefinition()
```
### GetElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Get the collection of elements from the page layout. Nesting
within <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref><b>is</b> preserved.</p>


```csharp
public IReadOnlyList<Element> GetElements()
```
### GetElementsAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Get the collection of <xref href="ArcGIS.Desktop.Layouts.Element" data-throw-if-not-resolved="false"></xref> from the page layout as a flattened list.
Nested groups within <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref> are <b>not</b> preserved.</p>


```csharp
public IReadOnlyList<Element> GetElementsAsFlattenedList()
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the Layout metadata.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetMetadata()
```
### GetPage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMPage?text=CIMPage" data-throw-if-not-resolved="false"></xref> for a layout.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMPage GetPage()
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Get a collection of the selected layout elements.</p>


```csharp
public ReadOnlyObservableCollection<Element> GetSelectedElements()
```
### GroupElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Group the collection of elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GroupElement GroupElements(IEnumerable<Element> elements)
```
### MapSeries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the map series associated with a layout.</p>


```csharp
public MapSeries MapSeries { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the name of the layout.</p>


```csharp
public string Name { get; }
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the OperationManager which is responsible for managing the undo/redo stack.</p>


```csharp
public OperationManager OperationManager { get; }
```
### PDFReadingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the order that elements in the PDF are read by assistive technologies.</p>


```csharp
public string[] PDFReadingOrder { get; }
```
### Print()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Print a layout using default printer settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Print()
```
### Print(PrinterSettingsInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Print a layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Print(PrinterSettingsInfo printerSettingsInfo)
```
### Print(PrinterSettingsInfo, MapSeriesExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Print pages from a layout's associated map series using a specialized collection of settings. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Print(PrinterSettingsInfo printerSettingsInfo, MapSeriesExportOptions mapSeriesExportOptions)
```
### ProjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the ID of the project that contains the layout.</p>


```csharp
public int ProjectID { get; }
```
### RefreshMapSeries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Refreshes the map series when the related map data changes. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void RefreshMapSeries()
```
### SaveAsFile(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Exports a layout to a new layout (.pagx) file. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SaveAsFile(string fullPathToPagXFile, bool overwrite)
```
### SelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Select the element within the page layout.</p>


```csharp
public void SelectElement(Element element)
```
### SelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Set the selected elements for the page layout.</p>


```csharp
public void SelectElements(IEnumerable<Element> elements)
```
### SendBackward(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Send the element backward within its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendBackward(Element element)
```
### SendBackward(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Send the elements backward within their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendBackward(IEnumerable<Element> elements)
```
### SendToBack(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Send the element to the back of its parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendToBack(Element element)
```
### SendToBack(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Send the elements to the back of their parent's element collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SendToBack(IEnumerable<Element> elements)
```
### SetDefinition(CIMLayout)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMLayout" data-throw-if-not-resolved="false"></xref> back to the element on the page layout. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMLayout cimLayout)
```
### SetMapSeries(MapSeries)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Sets the map series for a layout. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetMapSeries(MapSeries mapSeries)
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Sets the Layout metadata.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMetadata(string metadataXml)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Sets the name of the layout.   It is important that all layouts have a unique name so they can be easily referenced.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetPDFReadingOrder(string[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Applies the specified order that elements will be read by assistive technologies to the layout.</p>


```csharp
public void SetPDFReadingOrder(string[] pdfReadingOrder)
```
### SetPage(CIMPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMPage?text=CIMPage" data-throw-if-not-resolved="false"></xref> to the layout.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetPage(CIMPage page)
```
### SetPage(CIMPage, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMPage?text=CIMPage" data-throw-if-not-resolved="false"></xref> to the layout.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetPage(CIMPage page, bool resizeElements)
```
### ShowProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Opens the Layout Properties dialog.</p>


```csharp
public void ShowProperties()
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Gets the path of the layout in the project.</p>


```csharp
public string URI { get; }
```
### UnGroupElement(GroupElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Ungroup the elements contained in 'group'.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnGroupElement(GroupElement group)
```
### UnGroupElements(IEnumerable&lt;GroupElement&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Ungroup the elements contained in 'groups'.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnGroupElements(IEnumerable<GroupElement> groups)
```
### UnSelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Unselect the element on the page layout.</p>


```csharp
public void UnSelectElement(Element element)
```
### UnSelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.Layout.yml" sourcestartlinenumber="1">Unselect the elements on the page layout.</p>


```csharp
public void UnSelectElements(IEnumerable<Element> elements = null)
```


