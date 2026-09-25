# OCRManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Utility for performing Optical Character Recognition (OCR) operations.</p>


## Object Signature

```csharp
public sealed class OCRManager
```


## Members

### ExtractFromDocumentAsync(OCROptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Extracts information from a document image using the document image, page and output type specified in the <code class="paramref">ocrOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<OCROutput> ExtractFromDocumentAsync(OCROptions ocrOptions)
```
### ExtractFromDocumentAsync(OCROptions, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Extracts information from a document image using the document image, page and output type specified in the <code class="paramref">ocrOptions</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<OCROutput> ExtractFromDocumentAsync(OCROptions ocrOptions, CancellationToken cancellationToken)
```
### ExtractTextFromDocumentAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Extracts text from a document image using the <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref> output type.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<string> ExtractTextFromDocumentAsync(string documentFileName)
```
### ExtractTextFromDocumentAsync(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Extracts text from a specific page of a document image using the <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref> output type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<string> ExtractTextFromDocumentAsync(string documentFileName, int page)
```
### ExtractTextFromDocumentAsync(string, int, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Extracts text from a specific page of a document image using the <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref> output type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<string> ExtractTextFromDocumentAsync(string documentFileName, int page, CancellationToken cancellationToken)
```
### ExtractTextFromDocumentAsync(string, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Extracts text from a document image using the <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref> output type.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<string> ExtractTextFromDocumentAsync(string documentFileName, CancellationToken cancellationToken)
```
### GetDocumentPageCount(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Gets the number of pages in the specified document. See <xref href="ArcGIS.Core.OCR.OCRManager.IsValidDocumentForOCR(System.String)" data-throw-if-not-resolved="false"></xref> for information about the file extensions supported.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDocumentPageCount(string documentFileName)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Gets the OCRManager instance.</p>


```csharp
public static OCRManager Instance { get; }
```
### IsValidDocumentForOCR(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Gets if the specified document is suitable for Optical Character Recognittion (OCR) in order to extract text.</p>


```csharp
public bool IsValidDocumentForOCR(string documentFileName)
```
### SupportedFileFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Gets the current list of supported file extensions.  Use this as a filter to a File Open dialog.</p>


```csharp
public string SupportedFileFilter { get; }
```


