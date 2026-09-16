# DiagramEdgeElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement.yml" sourcestartlinenumber="1">Represents a generic diagram edge element.</p>


## Object Signature

```csharp
public sealed class DiagramEdgeElement : DiagramElement
```


## Members

### FromID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement.yml" sourcestartlinenumber="1">Gets the FromID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int FromID { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement.yml" sourcestartlinenumber="1">Gets the geometry type.  Always returns Polyline.</p>


```csharp
protected override GeometryType GeometryType { get; }
```
### ToID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement.yml" sourcestartlinenumber="1">Gets the ToID of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramEdgeElement" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int ToID { get; }
```


