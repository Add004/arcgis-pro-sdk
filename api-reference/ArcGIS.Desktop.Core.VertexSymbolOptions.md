# VertexSymbolOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Defines the options used for vertex symbols while sketching.</p>


## Object Signature

```csharp
public class VertexSymbolOptions
```


## Members

### VertexSymbolOptions(VertexSymbolType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Creates a new VertexSymbolOptions for the specified vertex type.</p>


```csharp
public VertexSymbolOptions(VertexSymbolType vertexSymbolType)
```
### AngleRotation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets and sets the angle rotation (in degrees). Default value is 0.</p>


```csharp
public double AngleRotation { get; set; }
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets and sets the color.  Default value is No color.</p>


```csharp
public CIMColor Color { get; set; }
```
### GetPointSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets the point symbol from the set of options.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol GetPointSymbol()
```
### MarkerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets and set the vertex marker type.  Default value is <xref href="ArcGIS.Desktop.Core.VertexMarkerType.Square" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public VertexMarkerType MarkerType { get; set; }
```
### OutlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets and sets the outline color. Default value is RGB value of (0, 128, 0).</p>


```csharp
public CIMColor OutlineColor { get; set; }
```
### OutlineWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets and sets the outline width. Default value is 1.5.</p>


```csharp
public double OutlineWidth { get; set; }
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.VertexSymbolOptions.yml" sourcestartlinenumber="1">Gets and sets the size (in points).  Default value is 5.</p>


```csharp
public double Size { get; set; }
```


