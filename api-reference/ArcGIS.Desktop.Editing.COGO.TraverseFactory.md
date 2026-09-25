# TraverseFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Provides static methods to create <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects.</p>


## Object Signature

```csharp
public sealed class TraverseFactory : ITraverseFactory
```


## Members

### ExtractTraverseFromDeedAsync(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a deed image using the <xref href="ArcGIS.Core.OCR.OCRManager" data-throw-if-not-resolved="false"></xref>.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(string deedFileName, SpatialReference spatialReference)
```
### ExtractTraverseFromDeedAsync(string, SpatialReference, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a deed image using the <xref href="ArcGIS.Core.OCR.OCRManager" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(string deedFileName, SpatialReference spatialReference, CancellationToken cancellationToken)
```
### ExtractTraverseFromDeedAsync(string, int, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a specific page of a deed image using the <xref href="ArcGIS.Core.OCR.OCRManager" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(string deedFileName, int page, SpatialReference spatialReference)
```
### ExtractTraverseFromDeedAsync(string, int, SpatialReference, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Extracts a set of tr<xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from a specific page of a deed image using the <xref href="ArcGIS.Core.OCR.OCRManager" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<IReadOnlyList<Traverse>> ExtractTraverseFromDeedAsync(string deedFileName, int page, SpatialReference spatialReference, CancellationToken cancellationToken)
```
### ExtractTraverseFromDeedText(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from raw deed text.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Traverse> ExtractTraverseFromDeedText(string deedText, SpatialReference spatialReference)
```
### ExtractTraverseFromDeedText(string, SpatialReference, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Extracts a set of <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> objects from raw deed text.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Traverse> ExtractTraverseFromDeedText(string deedText, SpatialReference spatialReference, CancellationToken cancellationToken)
```
### Import(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Imports an ArcMap traverse file and creates a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Traverse Import(string inputFilePath, SpatialReference spatialReference)
```
### ImportAsync(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Imports an ArcMap traverse file and creates a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Task<Traverse> ImportAsync(string inputFilePath, SpatialReference spatialReference)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for ITraverseFactory</p>


```csharp
public static ITraverseFactory Instance { get; }
```


