# OCROutputType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCROutputType.yml" sourcestartlinenumber="1">The output type for the OCR operation.   See <xref href="ArcGIS.Core.OCR.OCROptions.OutputType" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref> for usage.</p>


## Object Signature

```csharp
public enum OCROutputType
```


## Members

### TSV

- Kind: field

<p sourcefile="api/ArcGIS.Core.OCR.OCROutputType.yml" sourcestartlinenumber="1">Extracts information from the document image as Tab Separated Values (TSV). This provides detailed layout information
at multiple levels - blocks, paragraphs, lines, words; each accompanied by bounding box coordinates.</p>


```csharp
TSV = 1
```
### Text

- Kind: field

<p sourcefile="api/ArcGIS.Core.OCR.OCROutputType.yml" sourcestartlinenumber="1">Extracts information from the document image as text.</p>


```csharp
Text = 0
```


