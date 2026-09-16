# PresentationPageFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Provides methods to create new presentation pages.
Creates a new presentation page and inserts at the presentation's page collection.</p>


## Object Signature

```csharp
public class PresentationPageFactory : IPresentationPageFactory
```


## Members

### CreateBlankPage(Presentation, BlankPageTemplateType, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new blank page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PresentationPage CreateBlankPage(Presentation presentation, BlankPageTemplateType templateType, int insertIndex = -1)
```
### CreateImagePage(Presentation, string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new image page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ImagePresentationPage CreateImagePage(Presentation presentation, string imageURI, int insertIndex = -1)
```
### CreateMapPage(Presentation, Bookmark, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPresentationPage CreateMapPage(Presentation presentation, Bookmark bookmark, int insertIndex = -1)
```
### CreateMapPage(Presentation, Map, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPresentationPage CreateMapPage(Presentation presentation, Map map, int insertIndex = -1)
```
### CreateMapPage(Presentation, MapView, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPresentationPage CreateMapPage(Presentation presentation, MapView mapView, int insertIndex = -1)
```
### CreatePage(Presentation, CIMPresentationPage, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new page to the presentation using a CIM presentation page definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PresentationPage CreatePage(Presentation presentation, CIMPresentationPage cimPageDefinition, int insertIndex = -1)
```
### CreateVideoPage(Presentation, string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new video page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VideoPresentationPage CreateVideoPage(Presentation presentation, string videoURI, int insertIndex = -1)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationPageFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for IPresentationFactory</p>


```csharp
public static IPresentationPageFactory Instance { get; }
```


