# OCRTSVOutput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="1">Output from an OCR operation requesting TSV output; that is with <xref href="ArcGIS.Core.OCR.OCROptions.OutputType" data-throw-if-not-resolved="false"></xref> equal to <xref href="ArcGIS.Core.OCR.OCROutputType.TSV" data-throw-if-not-resolved="false"></xref>.
See <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions%2cSystem.Threading.CancellationToken)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class OCRTSVOutput : OCROutput
```

## Remarks

<p sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="1">The TSV output hierarchy is as follows:</p>
<ul sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="2">
<li sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="2"><xref href="ArcGIS.Core.OCR.OCRPage" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRBlock" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRParagraph" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRLine" data-throw-if-not-resolved="false"></xref> -&gt; <xref href="ArcGIS.Core.OCR.OCRWord" data-throw-if-not-resolved="false"></xref>.</li>
</ul>
 <p></p>
<p sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="6">That is, the <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> contains a set of <xref href="ArcGIS.Core.OCR.OCRPage?text=OCRPages" data-throw-if-not-resolved="false"></xref>.
Each <xref href="ArcGIS.Core.OCR.OCRPage" data-throw-if-not-resolved="false"></xref> contains a set of <xref href="ArcGIS.Core.OCR.OCRBlock?text=OCRBlocks" data-throw-if-not-resolved="false"></xref>.
Each <xref href="ArcGIS.Core.OCR.OCRBlock" data-throw-if-not-resolved="false"></xref> contains a set of <xref href="ArcGIS.Core.OCR.OCRParagraph?text=OCRParagraphs" data-throw-if-not-resolved="false"></xref>.
Each <xref href="ArcGIS.Core.OCR.OCRParagraph" data-throw-if-not-resolved="false"></xref> contains a set of <xref href="ArcGIS.Core.OCR.OCRLine?text=OCRLines" data-throw-if-not-resolved="false"></xref>.
Each <xref href="ArcGIS.Core.OCR.OCRLine" data-throw-if-not-resolved="false"></xref> contains a set of <xref href="ArcGIS.Core.OCR.OCRWord?text=OCRWords" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Pages

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="1">Gets the set of pages detected by the OCR operation.</p>


```csharp
public List<OCRPage> Pages { get; }
```


