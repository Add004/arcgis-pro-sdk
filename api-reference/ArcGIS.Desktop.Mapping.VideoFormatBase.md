# VideoFormatBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.VideoFormatBase.yml" sourcestartlinenumber="1">Represents the base class of a video format object that can be used to export a
<xref href="ArcGIS.Desktop.Presentations.Presentation?text=Presentation" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class VideoFormatBase : ExportFormat
```


## Members

### DefaultPageDuration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VideoFormatBase.yml" sourcestartlinenumber="1">Gets or sets the default page duration (in seconds).
The default duration is used when page's native duration is zero.</p>


```csharp
public double DefaultPageDuration { get; set; }
```
### FrameRate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VideoFormatBase.yml" sourcestartlinenumber="1">Gets and sets the number of images for each second of the video.</p>


```csharp
public double FrameRate { get; set; }
```
### HonorPageAdvancement

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VideoFormatBase.yml" sourcestartlinenumber="1">Gets or sets a flag indicating whether to honor CIMPresentationPage.IsAutomaticAdvancement.</p>


```csharp
public bool HonorPageAdvancement { get; set; }
```
### Quality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VideoFormatBase.yml" sourcestartlinenumber="1">Gets and sets a multiplier used for the data rate when exporting a video format. A higher value will increase the quality, but also the file size of the exported video.
The value can range from '0' to '1'.</p>


```csharp
public double Quality { get; set; }
```


