# ArcGIS.Core.OCR

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### OCRBlock

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRBlock.yml" sourcestartlinenumber="1">Represents a region of text within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


### OCRBoundingBox

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRBoundingBox.yml" sourcestartlinenumber="1">A rectangular container defined by coordinates that marks the exact location of detected text within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


### OCRExtensions

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRExtensions.yml" sourcestartlinenumber="1">Contains extension methods to extend ArcGIS.Core.OCR members.</p>


### OCRLine

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRLine.yml" sourcestartlinenumber="1">Represents a detected line within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


### OCRManager

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRManager.yml" sourcestartlinenumber="1">Utility for performing Optical Character Recognition (OCR) operations.</p>


### OCROptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCROptions.yml" sourcestartlinenumber="1">Represents the options used in performing Optical Character Recognition (OCR) operations.
See <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions%2cSystem.Threading.CancellationToken)" data-throw-if-not-resolved="false"></xref>.</p>


### OCROutput

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCROutput.yml" sourcestartlinenumber="1">Abstract class representing the types of output from an OCR operation according to the <xref href="ArcGIS.Core.OCR.OCROutputType" data-throw-if-not-resolved="false"></xref>.
See descendents <xref href="ArcGIS.Core.OCR.OCRTextOutput" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref>.</p>


### OCROutputType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.OCR.OCROutputType.yml" sourcestartlinenumber="1">The output type for the OCR operation.   See <xref href="ArcGIS.Core.OCR.OCROptions.OutputType" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref> for usage.</p>


### OCRPage

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRPage.yml" sourcestartlinenumber="1">Respresents a page within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


### OCRParagraph

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRParagraph.yml" sourcestartlinenumber="1">Represents a detected paragraph within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>


### OCRTSVOutput

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRTSVOutput.yml" sourcestartlinenumber="1">Output from an OCR operation requesting TSV output; that is with <xref href="ArcGIS.Core.OCR.OCROptions.OutputType" data-throw-if-not-resolved="false"></xref> equal to <xref href="ArcGIS.Core.OCR.OCROutputType.TSV" data-throw-if-not-resolved="false"></xref>.
See <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions%2cSystem.Threading.CancellationToken)" data-throw-if-not-resolved="false"></xref>.</p>


### OCRTextOutput

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRTextOutput.yml" sourcestartlinenumber="1">Output from an OCR operation requesting text output; that is with <xref href="ArcGIS.Core.OCR.OCROptions.OutputType" data-throw-if-not-resolved="false"></xref> equal to <xref href="ArcGIS.Core.OCR.OCROutputType.Text" data-throw-if-not-resolved="false"></xref>.
See <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions)" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Core.OCR.OCRManager.ExtractFromDocumentAsync(ArcGIS.Core.OCR.OCROptions%2cSystem.Threading.CancellationToken)" data-throw-if-not-resolved="false"></xref>.</p>


### OCRWord

- Kind: class

<p sourcefile="api/ArcGIS.Core.OCR.OCRWord.yml" sourcestartlinenumber="1">Represents a detected word within a document image.
Used within the components of an <xref href="ArcGIS.Core.OCR.OCRTSVOutput" data-throw-if-not-resolved="false"></xref> instance.</p>




