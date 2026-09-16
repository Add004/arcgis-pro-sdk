# OverlayControlPositionChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.OverlayControlPositionChangedEventArgs.yml" sourcestartlinenumber="1">Position arguments for position changed event in <xref href="ArcGIS.Desktop.Mapping.MapViewOverlayControl" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class OverlayControlPositionChangedEventArgs : EventArgs
```


## Members

### XPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.OverlayControlPositionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the pixel offset for the left.</p>


```csharp
public double XPosition { get; }
```
### XRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.OverlayControlPositionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the horizontal offset of the control as a percent from 0 (left edge), to 1 (right edge).</p>


```csharp
public double XRatio { get; }
```
### YPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.OverlayControlPositionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the pixel offset for the top.</p>


```csharp
public double YPosition { get; }
```
### YRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.OverlayControlPositionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the vertical offset of the control as a percent from 0 (top edge), to 1 (bottom edge).</p>


```csharp
public double YRatio { get; }
```


