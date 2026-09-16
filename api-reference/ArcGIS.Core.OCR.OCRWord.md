# OCRWord

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">Represents a detected word within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


## Object Signature

```csharp
public sealed class OCRWord
```

## Remarks

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">The TSV output hierarchy is as follows:</p>
<ul sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="2">
<li sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="2"><xref href="ArcGIS.Core.OCR.OCRPage" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRBlock" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRParagraph" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRLine" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRWord" data-throw-if-not-resolved="false"></xref>.</li>
</ul>
 <p></p>
<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="6">That is, a set of <xref href="ArcGIS.Core.OCR.OCRWord?text=OCRWords" data-throw-if-not-resolved="false"></xref> are in an <xref href="ArcGIS.Core.OCR.OCRLine" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### OCRWord(OCRBoundingBox)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">Creates an instance of <xref href="ArcGIS.Core.OCR.OCRWord" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public OCRWord(OCRBoundingBox boundingBox)
```
### BoundingBox

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">Gets the bounding box of the word.</p>


```csharp
public OCRBoundingBox BoundingBox { get; }
```
### Confidence

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">Gets the confidence that the word recognized by the OCR engine is correct. This is a percentage based score (0 to 100).</p>


```csharp
public double Confidence { get; }
```
### Content

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">Gets the word content.</p>


```csharp
public string Content { get; }
```


