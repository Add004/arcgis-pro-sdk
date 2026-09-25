# OCRBoundingBox

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">A rectangular container defined by coordinates that marks the exact location of detected text within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


## Object Signature

```csharp
public sealed class OCRBoundingBox
```


## Members

### OCRBoundingBox(int, int, int, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">Creates an instance of <xref href="ArcGIS.Core.OCR.OCRBoundingBox" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public OCRBoundingBox(int x, int y, int width, int height)
```
### Expand(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.OCR.OCRBoundingBox" data-throw-if-not-resolved="false"></xref>  with the x,y, width and height scaled according to the ratios.</p>


```csharp
public OCRBoundingBox Expand(double xRatio, double yRatio)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">Gets the height of the bounding box.</p>


```csharp
public int Height { get; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">Gets the width of the bounding box.</p>


```csharp
public int Width { get; }
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">Gets the x position of the lower left of the bounding box.</p>


```csharp
public int X { get; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">Gets the y position of the lower left of the bounding box.</p>


```csharp
public int Y { get; }
```


