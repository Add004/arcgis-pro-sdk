# OCRExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.OCR.html">OCR</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Core.OCR.OCRExtensions.yml" sourcestartlinenumber="1">Contains extension methods to extend ArcGIS.Core.OCR members.</p>


## Object Signature

```csharp
public static class OCRExtensions
```


## Members

### ExtractTraverseFromDeedAsync(OCRManager, string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRExtensions.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a deed image.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(this OCRManager OCRManager, string deedFileName, SpatialReference spatialReference)
```
### ExtractTraverseFromDeedAsync(OCRManager, string, SpatialReference, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRExtensions.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a deed image.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(this OCRManager OCRManager, string deedFileName, SpatialReference spatialReference, CancellationToken cancellationToken)
```
### ExtractTraverseFromDeedAsync(OCRManager, string, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRExtensions.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a specific page of a deed image.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(this OCRManager OCRManager, string deedFileName, int page, SpatialReference spatialReference)
```
### ExtractTraverseFromDeedAsync(OCRManager, string, int, SpatialReference, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Core.OCR.OCRExtensions.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a specific page of a deed image.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(this OCRManager OCRManager, string deedFileName, int page, SpatialReference spatialReference, CancellationToken cancellationToken)
```


