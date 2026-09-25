# Presentation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Represents a presentation.</p>


## Object Signature

```csharp
public class Presentation : ViewModelBase
```


## Members

### AddBlankPage(BlankPageTemplateType, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Adds a new blank page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PresentationPage AddBlankPage(BlankPageTemplateType templateType, int insertIndex)
```
### AddImagePage(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Adds a new image page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ImagePresentationPage AddImagePage(string imageURI, int insertIndex)
```
### AddMapPage(Bookmark, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPresentationPage AddMapPage(Bookmark bookmark, int insertIndex)
```
### AddMapPage(Map, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPresentationPage AddMapPage(Map map, int insertIndex)
```
### AddMapPage(MapView, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPresentationPage AddMapPage(MapView mapView, int insertIndex)
```
### AddVideoPage(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Adds a new video page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VideoPresentationPage AddVideoPage(string videoURI, int insertIndex)
```
### CopyPages(IEnumerable&lt;PresentationPage&gt;, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Copies a list of pages and insert the copied pages at the specified position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CopyPages(IEnumerable<PresentationPage> pages, int insertIndex)
```
### CopyPages(IEnumerable&lt;int&gt;, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Copies a list of pages and insert the copied pages at the specified position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CopyPages(IEnumerable<int> pageIndices, int insertIndex)
```
### DeletePage(PresentationPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Delete a page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeletePage(PresentationPage page)
```
### DeletePage(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Deletes a page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeletePage(int pageIndex)
```
### DeletePages(IEnumerable&lt;PresentationPage&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Deletes a list of pages. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeletePages(IEnumerable<PresentationPage> pages)
```
### DeletePages(IEnumerable&lt;int&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Deletes a list of pages. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeletePages(IEnumerable<int> pageIndices)
```
### Export(ExportFormat, PresentationExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Exports the presentation to a variety of formats (e.g., PDF, video, image series). This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat, PresentationExportOptions options)
```
### GetAllPages()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets all the pages in the presentation.</p>


```csharp
public IEnumerable<PresentationPage> GetAllPages()
```
### GetAspectRatio()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the aspect ratio of the presentation.</p>


```csharp
public (int width, int height) GetAspectRatio()
```
### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets whether the presentation's metadata can be edited or not.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCanEditMetadata()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the presentation's CIM definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPresentation GetDefinition()
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the presentation's metadata.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetMetadata()
```
### GetPage(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Get a page by index.</p>


```csharp
public PresentationPage GetPage(int pageIndex)
```
### GetPageSettings()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMPage?text=CIMPage" data-throw-if-not-resolved="false"></xref> for the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPage GetPageSettings()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the name of the presentation.</p>


```csharp
public string Name { get; }
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the OperationManager which is responsible for managing the undo/redo stack.</p>


```csharp
public OperationManager OperationManager { get; }
```
### PageCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the total number of pages in the presentation.</p>


```csharp
public int PageCount { get; }
```
### ProjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the ID of the project that contains the presentation.</p>


```csharp
public int ProjectID { get; }
```
### SaveAsFile(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Exports a presentation to a new presentation (.prsx) file. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveAsFile(string fullPathToPrsxFile, bool overwrite)
```
### SetAspectRatio(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Changes the aspect ratio of the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetAspectRatio(int width, int height)
```
### SetDefinition(CIMPresentation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMPresentation" data-throw-if-not-resolved="false"></xref> to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMPresentation cimPresentation)
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Sets the presentation's metadata.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMetadata(string metadataXml)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Sets the name of the presentation. It is important that all presentations have a unique name so they can be easily referenced. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetPageSettings(CIMPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMPage?text=CIMPage" data-throw-if-not-resolved="false"></xref> to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPageSettings(CIMPage pageSettings)
```
### ShowProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Opens the Presentation Properties dialog.</p>


```csharp
public void ShowProperties()
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.Presentation.yml" sourcestartlinenumber="1">Gets the path to the presentation in the project.</p>


```csharp
public string URI { get; }
```


