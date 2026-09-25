# OCROptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Represents the options used in performing Optical Character Recognition (OCR) operations.
See <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions%2cSystem.Threading.CancellationToken)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class OCROptions
```


## Members

### OCROptions(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Creates an instance of the <xref href="ArcGIS.Core.OCR.OCROptions" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public OCROptions(string documentFileName)
```
### OCROptions(string, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Creates an instance of the <xref href="ArcGIS.Core.OCR.OCROptions" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public OCROptions(string documentFileName, int page)
```
### DocumentFileName

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Gets the document filename to be used in an OCR operation.</p>


```csharp
public string DocumentFileName { get; }
```
### Model

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Gets and sets the language model used in the OCR operation.  The default value is &quot;eng&quot; meaning that the
default training data file used is &quot;eng.traineddata&quot;.</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="6">If no language model is specified, then the default &quot;eng&quot; model is used.</p>


```csharp
public string Model { get; set; }
```
### OutputType

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Gets and sets the OCR output type.  The default value is <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public OCROutputType OutputType { get; set; }
```
### Page

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Gets the page to extract information from.  The default value is -1.</p>


```csharp
public int Page { get; }
```
### Resolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Gets and sets the resolution used in converting .pdf files to .tiff for the OCR processing. The value is in dots per inch (DPI).  The default value is 300.</p>


```csharp
public long Resolution { get; set; }
```


