# MapPresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Represents a map presentation page.</p>


## Object Signature

```csharp
public sealed class MapPresentationPage : PresentationPage, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```


## Members

### IsActivated

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Gets whether the map is activated or not.</p>


```csharp
public bool IsActivated { get; }
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Gets the path to the map associated with the presentation page in the project.</p>


```csharp
public string MapURI { get; }
```
### MapViewDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Gets the map view definition.</p>


```csharp
public CIMMapView MapViewDefinition { get; }
```
### SetCIMMapView(CIMMapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map view definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCIMMapView(CIMMapView cimMapView)
```
### SetCamera(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map page extent using an envelope. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Envelope extent)
```
### SetCamera(Bookmark)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map page extent defined in a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Bookmark bookmark)
```
### SetCamera(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map page extent to a camera position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Camera camera)
```
### SetCamera(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map page extent using the layer's extent. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Layer layer)
```
### SetCamera(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map page extent using the extent of multiple layers. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(IEnumerable<Layer> layers)
```
### SetMapSource(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.MapPresentationPage.yml" sourcestartlinenumber="1">Sets the map source of the map presentation page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMapSource(Map map)
```


