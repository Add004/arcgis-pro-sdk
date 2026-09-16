# AnimationExportParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Properties used to export an animation.</p>


## Object Signature

```csharp
public class AnimationExportParameters
```


## Members

### AnimationExportParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Initialize a new instance of an AnimationExportParameters.</p>


```csharp
public AnimationExportParameters()
```
### EndFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets the last frame to be exported. When set to a negative value, export will stop at the end of the animation.</p>


```csharp
public int EndFrame { get; set; }
```
### FilePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets the file path to export to.</p>


```csharp
public string FilePath { get; set; }
```
### FrameRate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets the number of images for each second of the animation.</p>


```csharp
public double FrameRate { get; set; }
```
### Quality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets a multiplier used for the data rate when exporting a video format.  A higher value will increase the quality, but also the file size of the exported video.
The value can range from '0' to '1'.</p>


```csharp
public double Quality { get; set; }
```
### ResolutionHeight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets the pixel height of the export.</p>


```csharp
public int ResolutionHeight { get; set; }
```
### ResolutionWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets the pixel width of the export.</p>


```csharp
public int ResolutionWidth { get; set; }
```
### StartFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnimationExportParameters.yml" sourcestartlinenumber="1">Gets and sets the frame to start exporting from.  When set to zero or less, export will start from the beginning of the animation.</p>


```csharp
public int StartFrame { get; set; }
```


