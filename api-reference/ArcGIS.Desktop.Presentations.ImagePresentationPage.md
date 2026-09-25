# ImagePresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.ImagePresentationPage.yml" sourcestartlinenumber="1">Represents an image presentation page.</p>


## Object Signature

```csharp
public sealed class ImagePresentationPage : PresentationPage, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```


## Members

### ImageURL

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.ImagePresentationPage.yml" sourcestartlinenumber="1">Gets the source path to the image.</p>


```csharp
public string ImageURL { get; }
```
### SetImageSource(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.ImagePresentationPage.yml" sourcestartlinenumber="1">Sets the image source. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetImageSource(string imageURL)
```


