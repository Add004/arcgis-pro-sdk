# ElevationCapturing

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Manages Elevation capture settings for Editing workflows.</p>


## Object Signature

```csharp
public static class ElevationCapturing
```


## Members

### CaptureMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Gets the current mode for capturing elevation when an edit is performed.</p>


```csharp
public static ElevationCaptureMode CaptureMode { get; }
```
### CurrentEditedMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">The currently edited map</p>


```csharp
public static Map CurrentEditedMap { get; }
```
### ElevationConstantValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Gets or sets the current value to be used with <xref href="ArcGIS.Desktop.Editing.ElevationCaptureMode.Constant" data-throw-if-not-resolved="false"></xref> mode elevation capturing.</p>


```csharp
public static double ElevationConstantValue { get; set; }
```
### ElevationSurfaceLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Gets or sets the elevation surface layer to be used with <xref href="ArcGIS.Desktop.Editing.ElevationCaptureMode.Surface" data-throw-if-not-resolved="false"></xref> mode elevation capturing.</p>


```csharp
public static ElevationSurfaceLayer ElevationSurfaceLayer { get; set; }
```
### HasSurfaces

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Gets whether the current Map has any usable elevation surface layers</p>


```csharp
public static bool HasSurfaces { get; }
```
### QueryElevationSurfaceLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Obtains the usable elevation surface layers that are stored in the currently edited map.</p>


```csharp
public static IEnumerable<ElevationSurfaceLayer> QueryElevationSurfaceLayers()
```
### QueryElevationSurfaceLayers(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Obtains the usable elevation surface layers that are stored in the specified map.</p>


```csharp
public static IEnumerable<ElevationSurfaceLayer> QueryElevationSurfaceLayers(Map map)
```
### SetCaptureModeAsync(ElevationCaptureMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ElevationCapturing.yml" sourcestartlinenumber="1">Sets the mode for capturing elevation.</p>


```csharp
public static Task SetCaptureModeAsync(ElevationCaptureMode mode)
```


