# ArrowInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Specifies the characteristics of an arrow graphic for use with the
<xref href="ArcGIS.Desktop.Layouts.GraphicFactory" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class ArrowInfo
```


## Members

### ArrowInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public ArrowInfo()
```
### ArrowHeadKey

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Gets and sets the arrowhead key for the respective arrow
head marker from the <xref href="ArcGIS.Desktop.Layouts.ArrowInfo.DefaultArrowStyleName" data-throw-if-not-resolved="false"></xref></p>


```csharp
public string ArrowHeadKey { get; set; }
```
### ArrowOnBothEnds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Gets and sets whether the arrow should have an arrow placed
at both ends or not.</p>


```csharp
public bool ArrowOnBothEnds { get; set; }
```
### ArrowSizePoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">The size of the arrow head in points</p>


```csharp
public double ArrowSizePoints { get; set; }
```
### DefaultArrowHeadKey

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Default arrowhead style item key for the arrow symbol lookup</p>


```csharp
public const string DefaultArrowHeadKey = "Arrowhead 6_Arrowheads_3"
```
### DefaultArrowHeadKeys

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Available arrowhead style item keys</p>


```csharp
public static readonly IReadOnlyList<string> DefaultArrowHeadKeys
```
### DefaultArrowStyleName

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">Default style used for the arrowhead marker symbol lookup</p>


```csharp
public const string DefaultArrowStyleName = "ArcGIS 2D"
```
### LineWidthPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ArrowInfo.yml" sourcestartlinenumber="1">The width of the arrow line in points</p>


```csharp
public double LineWidthPoints { get; set; }
```


