# IMapViewOverlayControl

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">Implement to add an overlay control over a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref> or use <xref href="ArcGIS.Desktop.Mapping.MapViewOverlayControl" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public interface IMapViewOverlayControl
```


## Members

### CanMove

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates a move handle should be attached to allow the control to be moved around over the map.</p>


```csharp
bool CanMove { get; }
```
### CanResizeHorizontally

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates that left and right resize handles should be attached to the control.</p>


```csharp
bool CanResizeHorizontally { get; }
```
### CanResizeVertically

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates that top and bottom resize handles should be attached to the control.</p>


```csharp
bool CanResizeVertically { get; }
```
### Control

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">The control to place over the MapView.</p>


```csharp
FrameworkElement Control { get; }
```
### InitialXRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">The initial horizontal position of the control as a percent.  Can be from 0 (left edge), to 1 (right edge).</p>


```csharp
double InitialXRatio { get; }
```
### InitialYRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">The initial vertical position of the control as a percent.  Can be from 0 (top edge), to 1 (bottom edge).</p>


```csharp
double InitialYRatio { get; }
```
### RelativePosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapViewOverlayControl.yml" sourcestartlinenumber="1">When the window is resized the distance from the edge is maintained relative to a corner of the map.</p>


```csharp
OverlayControlRelativePosition RelativePosition { get; }
```


