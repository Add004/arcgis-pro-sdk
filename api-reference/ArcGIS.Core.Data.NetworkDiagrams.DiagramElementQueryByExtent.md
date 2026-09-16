# DiagramElementQueryByExtent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByExtent.yml" sourcestartlinenumber="1">Represents a diagram element query based on a geographical extent.</p>


## Object Signature

```csharp
public class DiagramElementQueryByExtent : DiagramElementQueryByElementTypes
```


## Members

### DiagramElementQueryByExtent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByExtent.yml" sourcestartlinenumber="1">Initializes a new instance of the DiagramElementQueryByExtent class.</p>


```csharp
public DiagramElementQueryByExtent()
```
### AddContents

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByExtent.yml" sourcestartlinenumber="1">Indicates whether or not the &quot;searching&quot; envelope must be enlarged to include the extent of any containers that are partially within the specified envelope.
False to return the diagram features which strictly intersect the specified envelope(default).
True to enlarge the &quot;searching&quot; envelope so it includes the extent of any containers that are partially within the specified envelope.</p>


```csharp
public bool AddContents { get; set; }
```
### ExtentOfInterest

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByExtent.yml" sourcestartlinenumber="1">The extent <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> used to search for diagram elements; that is, the extent that the resulting queried diagram elements will intersect.</p>


```csharp
public Envelope ExtentOfInterest { get; set; }
```


