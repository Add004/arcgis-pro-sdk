# MapViewOverlayControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Implements IMapViewOverlayControl to add an overlay control over a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapViewOverlayControl : IMapViewOverlayControl, INotifyPropertyChanged
```


## Members

### MapViewOverlayControl(FrameworkElement, bool, bool, bool, OverlayControlRelativePosition, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Sets the properties for IMapViewOverlayControl.</p>


```csharp
public MapViewOverlayControl(FrameworkElement control, bool canMove = true, bool canResizeHorizontally = true, bool canResizeVertically = true, OverlayControlRelativePosition relativePosition = OverlayControlRelativePosition.CurrentPosition, double initialXRatio = 0, double initialYRatio = 0)
```
### CanMove

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates a move handle should be attached to allow the control to be moved around over the map.</p>


```csharp
public virtual bool CanMove { get; set; }
```
### CanResizeHorizontally

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates that left and right resize handles should be attached to the control.</p>


```csharp
public virtual bool CanResizeHorizontally { get; set; }
```
### CanResizeVertically

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates that top and bottom resize handles should be attached to the control.</p>


```csharp
public virtual bool CanResizeVertically { get; set; }
```
### Control

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">The control to place over the MapView.</p>


```csharp
public FrameworkElement Control { get; }
```
### FillMoveHandle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates a move handle should be usable behind any area of the control that is not hit test visible.</p>


```csharp
public virtual bool FillMoveHandle { get; set; }
```
### InitialXRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">The initial horizontal position of the control as a percent.  Can be from 0 (left edge), to 1 (right edge).</p>


```csharp
public virtual double InitialXRatio { get; }
```
### InitialYRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">The initial vertical position of the control as a percent.  Can be from 0 (top edge), to 1 (bottom edge).</p>


```csharp
public virtual double InitialYRatio { get; }
```
### MaintainAspectRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Indicates that only corner resize handles should be attached to the control when vertical and horizontal resize is allowed.</p>


```csharp
public virtual bool MaintainAspectRatio { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">The margin to maintain from the view border when moving the overlay.</p>


```csharp
public virtual Thickness Margin { get; set; }
```
### NotifyPropertyChanged(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Used to invoke a PropertyChanged.</p>


```csharp
protected virtual void NotifyPropertyChanged(string propertyName = null)
```
### PositionChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Occurs when the position or relative position to the MapView is changed.</p>


```csharp
public event EventHandler<OverlayControlPositionChangedEventArgs> PositionChanged
```
### PropertyChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Occurs when a property is changed.</p>


```csharp
public event PropertyChangedEventHandler PropertyChanged
```
### RaisePositionChanged(OverlayControlPositionChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">Used to invoke a PositionChanged.</p>


```csharp
public virtual void RaisePositionChanged(OverlayControlPositionChangedEventArgs args)
```
### RelativePosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapViewOverlayControl.yml" sourcestartlinenumber="1">When the window is resized the distance from the edge is maintained relative to the top left or bottom right corner of the map.</p>


```csharp
public virtual OverlayControlRelativePosition RelativePosition { get; set; }
```


