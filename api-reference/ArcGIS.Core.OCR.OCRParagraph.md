# OCRParagraph

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="1">Represents a detected paragraph within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


## Object Signature

```csharp
public sealed class OCRParagraph
```

## Remarks

<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="1">The TSV output hierarchy is as follows:</p>
<ul sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="2">
<li sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="2"><xref href="ArcGIS.Core.OCR.OCRPage" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRBlock" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRParagraph" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRLine" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRWord" data-throw-if-not-resolved="false"></xref>.</li>
</ul>
 <p></p>
<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="6">That is, an <xref href="ArcGIS.Core.OCR.OCRParagraph" data-throw-if-not-resolved="false"></xref> contains a set of <xref href="ArcGIS.Core.OCR.OCRLine?text=OCRLines" data-throw-if-not-resolved="false"></xref> and a set of
<xref href="ArcGIS.Core.OCR.OCRParagraph?text=OCRParagraphs" data-throw-if-not-resolved="false"></xref> are in an <xref href="ArcGIS.Core.OCR.OCRBlock" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### OCRParagraph(OCRBoundingBox)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="1">Creates an instance of <xref href="ArcGIS.Core.OCR.OCRParagraph" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public OCRParagraph(OCRBoundingBox boundingBox)
```
### BoundingBox

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="1">Gets the bounding box of the paragraph.</p>


```csharp
public OCRBoundingBox BoundingBox { get; }
```
### Lines

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="1">Gets the set of lines within the paragraph.</p>


```csharp
public List<OCRLine> Lines { get; }
```


