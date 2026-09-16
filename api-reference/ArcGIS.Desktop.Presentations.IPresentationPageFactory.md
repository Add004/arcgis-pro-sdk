# IPresentationPageFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Provides access to presentation page creation members.</p>


## Object Signature

```csharp
public interface IPresentationPageFactory
```


## Members

### CreateBlankPage(Presentation, BlankPageTemplateType, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new blank page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
PresentationPage CreateBlankPage(Presentation presentation, BlankPageTemplateType templateType, int insertIndex)
```
### CreateImagePage(Presentation, string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new image page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
ImagePresentationPage CreateImagePage(Presentation presentation, string imageURI, int insertIndex)
```
### CreateMapPage(Presentation, Bookmark, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
MapPresentationPage CreateMapPage(Presentation presentation, Bookmark bookmark, int insertIndex)
```
### CreateMapPage(Presentation, Map, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
MapPresentationPage CreateMapPage(Presentation presentation, Map map, int insertIndex)
```
### CreateMapPage(Presentation, MapView, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new map page to the presentation based on a map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
MapPresentationPage CreateMapPage(Presentation presentation, MapView mapView, int insertIndex)
```
### CreatePage(Presentation, CIMPresentationPage, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new page to the presentation using a CIM presentation page definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
PresentationPage CreatePage(Presentation presentation, CIMPresentationPage cimPageDefinition, int insertIndex)
```
### CreateVideoPage(Presentation, string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPageFactory.yml" sourcestartlinenumber="1">Adds a new video page to the presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
VideoPresentationPage CreateVideoPage(Presentation presentation, string videoURI, int insertIndex)
```


