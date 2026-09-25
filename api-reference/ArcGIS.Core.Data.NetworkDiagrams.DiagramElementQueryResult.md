# DiagramElementQueryResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryResult.yml" sourcestartlinenumber="1">Represents the result of a diagram element query.</p>


## Object Signature

```csharp
public sealed class DiagramElementQueryResult
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryResult.yml" sourcestartlinenumber="1">This object is created by a call to <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.QueryDiagramElements(ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByElementTypes)" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.QueryDiagramElements(ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByExtent)" data-throw-if-not-resolved="false"></xref>, or
<xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.QueryDiagramElements(ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryByObjectIDs)" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### DiagramContainerElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryResult.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramContainerElement" data-throw-if-not-resolved="false"></xref>s returned by the query.</p>


```csharp
public IReadOnlyList<DiagramContainerElement> DiagramContainerElements { get; }
```
### DiagramEdgeElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryResult.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement" data-throw-if-not-resolved="false"></xref>s returned by the query.</p>


```csharp
public IReadOnlyList<DiagramEdgeElement> DiagramEdgeElements { get; }
```
### DiagramJunctionElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramElementQueryResult.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramJunctionElement" data-throw-if-not-resolved="false"></xref>s returned by the query.</p>


```csharp
public IReadOnlyList<DiagramJunctionElement> DiagramJunctionElements { get; }
```


