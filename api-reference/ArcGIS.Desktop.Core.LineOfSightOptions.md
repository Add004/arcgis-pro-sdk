# LineOfSightOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Defines the options used for the line of sight analysis.</p>


## Object Signature

```csharp
public class LineOfSightOptions
```


## Members

### LineOfSightOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Creates a new LineOfSightOptions.</p>


```csharp
public LineOfSightOptions()
```
### LineOfSightOptions(LineOfSightOptions)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Creates a new LineOfSightOptions from an existing LineOfSightOptions.</p>


```csharp
public LineOfSightOptions(LineOfSightOptions copy)
```
### ExtendLines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets whether to extend lines to the maximum distance.  Default value is false.</p>


```csharp
public bool ExtendLines { get; set; }
```
### LineWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets the line width used in the line of sight.  Default value is 1.</p>


```csharp
public double LineWidth { get; set; }
```
### NotVisibleColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets the not visible color of the line of sight. Default value is RGB value of (200, 28, 139).</p>


```csharp
public CIMColor NotVisibleColor { get; set; }
```
### OutOfRangeColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets the out of range color of the line of sight. Default value is RGB value of (183, 183, 183).</p>


```csharp
public CIMColor OutOfRangeColor { get; set; }
```
### ShowEditOverlay

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets whether to show the edit overlay. Default value is true.</p>


```csharp
public bool ShowEditOverlay { get; set; }
```
### ShowIntersectionDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets whether to show the intersection distance.  Default value is false.</p>


```csharp
public bool ShowIntersectionDistance { get; set; }
```
### VisibleColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets the visible color of the line of sight. Default value is RGB value of (77, 172, 38).</p>


```csharp
public CIMColor VisibleColor { get; set; }
```
### WireframeColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.LineOfSightOptions.yml" sourcestartlinenumber="1">Gets and sets the wireframe color of the line of sight. Default value is RGB value of (255, 170, 0).</p>


```csharp
public CIMColor WireframeColor { get; set; }
```


