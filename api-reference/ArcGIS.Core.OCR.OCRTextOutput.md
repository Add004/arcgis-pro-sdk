# OCRTextOutput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRTextOutput.yml" sourcestartlinenumber="1">Output from an OCR operation requesting text output; that is with <xref href="ArcGIS.Core.OCR.OCROptions.OutputType" data-throw-if-not-resolved="false"></xref> equal to <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref>.
See <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions%2cSystem.Threading.CancellationToken)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class OCRTextOutput : OCROutput
```


## Members

### Text

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRTextOutput.yml" sourcestartlinenumber="1">Gets the text detected by the OCR operation.</p>


```csharp
public string Text { get; }
```


