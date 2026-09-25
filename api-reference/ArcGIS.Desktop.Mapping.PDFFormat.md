# PDFFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Represents a Portable Document Format (PDF) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class PDFFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">PDF files are designed to be consistently viewable and printable across different platforms.
They are commonly used for distributing documents on the Web and are becoming a standard interchange format for content delivery.
PDFs are editable in many graphics applications and can retain annotation, labeling, and attribute data for map layers.
PDF exports from support embedding of fonts and thus can display symbology correctly even if the user does not have Esri fonts installed.</p>


## Members

### PDFFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Initialize a new instance of PDFFormat.</p>


```csharp
public PDFFormat()
```
### AccessibilityReadingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the ordered list of element names that defines the reading order for assistive technologies such as screen readers.</p>


```csharp
public string[] AccessibilityReadingOrder { get; set; }
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the document author for PDF accessibility.</p>


```csharp
public string Author { get; set; }
```
### DoCompressVectorGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls compression of vector and text portions of the output file. Image compression is defined separately.</p>


```csharp
public bool DoCompressVectorGraphics { get; set; }
```
### DoConvertCharacterMarkerSymbolsToPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the conversion of character marker symbols to polygon.</p>


```csharp
public bool DoConvertCharacterMarkerSymbolsToPolygon { get; set; }
```
### DoEmbedFonts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the embedding of fonts in the export file.</p>


```csharp
public bool DoEmbedFonts { get; set; }
```
### DoFullRasterization

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the full rasterization in export file.</p>


```csharp
public bool DoFullRasterization { get; set; }
```
### DoRemoveThinLineArtifact

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean to export raster content as a single tile.</p>


```csharp
public bool DoRemoveThinLineArtifact { get; set; }
```
### DoSimulateOverprint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets if the effect of overprinting is simulated on symbol layers.</p>


```csharp
public bool DoSimulateOverprint { get; set; }
```
### HasColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets if a color profile is embedded.</p>


```csharp
public bool HasColorProfile { get; set; }
```
### HasGeoRefInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that enables the export of coordinate system information for each map inserted into the output PDF file.</p>


```csharp
public bool HasGeoRefInfo { get; set; }
```
### ImageCompression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the compression scheme used to compress image or raster data in the output file.</p>


```csharp
public ImageCompression ImageCompression { get; set; }
```
### ImageCompressionQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">This value (0–100) controls the amount of compression applied to the output image. With a JPEG image, quality is
adversely affected the more compression is applied. A higher quality (highest = 100) setting will produce sharper
images and larger file sizes. A lower quality setting will produce more image artifacts and smaller files.</p>


```csharp
public int ImageCompressionQuality { get; set; }
```
### ImageQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the output image quality - the draw resolution of map layers that draw as rasters.</p>


```csharp
public ImageQuality ImageQuality { get; set; }
```
### IncludeAccessibilityTags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that enables if accessibility tags are added to the output PDF document.</p>


```csharp
public bool IncludeAccessibilityTags { get; set; }
```
### IncludeNonVisibleMapLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets if the output will have non-visible map layers.</p>


```csharp
public bool IncludeNonVisibleMapLayers { get; set; }
```
### Keywords

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the document keywords for PDF accessibility.</p>


```csharp
public string Keywords { get; set; }
```
### LanguageCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the language code for PDF accessibility tags.</p>


```csharp
public string LanguageCode { get; set; }
```
### LayersAndAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the property that controls inclusion of PDF layer and PDF object data (attributes) in the export file.</p>


```csharp
public LayersAndAttributes LayersAndAttributes { get; set; }
```
### MasterPassword

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the master password to protect the file.  The password will need to be entered for editing and printing file.</p>


```csharp
public string MasterPassword { get; set; }
```
### Password

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the password to protect the file.  The password will need to be entered when the file is opened.</p>


```csharp
public string Password { get; set; }
```
### RemoveLayoutBackground

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets if the output will have white background.</p>


```csharp
public bool RemoveLayoutBackground { get; set; }
```
### SecurityPermission

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the security permission.</p>


```csharp
public PDFSecurityPermission SecurityPermission { get; set; }
```
### Subject

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the document subject for PDF accessibility.</p>


```csharp
public string Subject { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PDFFormat.yml" sourcestartlinenumber="1">Gets or sets the document title for PDF accessibility.</p>


```csharp
public string Title { get; set; }
```


