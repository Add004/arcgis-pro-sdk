# VideoPresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Represents a video presentation page.</p>


## Object Signature

```csharp
public sealed class VideoPresentationPage : PresentationPage, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```


## Members

### EndTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Gets the end time of the video in seconds.</p>


```csharp
public double EndTime { get; }
```
### FullLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Gets the full duration of the source video in seconds.</p>


```csharp
public double FullLength { get; }
```
### SetEndTime(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Sets the page end time in seconds.</p>


```csharp
public void SetEndTime(double endTime)
```
### SetStartTime(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Sets the start time of the video in seconds.</p>


```csharp
public void SetStartTime(double startTime)
```
### SetVideoSource(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Sets the video source. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVideoSource(string videoURL)
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Gets the start time of the video in seconds.</p>


```csharp
public double StartTime { get; }
```
### VideoURL

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.VideoPresentationPage.yml" sourcestartlinenumber="1">Gets the source path to the video file associated with the page.</p>


```csharp
public string VideoURL { get; }
```


