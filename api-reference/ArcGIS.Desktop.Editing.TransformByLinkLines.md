# TransformByLinkLines

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformByLinkLines.yml" sourcestartlinenumber="1">Transform using a collection of <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> geometries as links.</p>


## Object Signature

```csharp
public sealed class TransformByLinkLines : TransformMethod
```


## Members

### TransformByLinkLines()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformByLinkLines.yml" sourcestartlinenumber="1">Constructs a new <xref href="ArcGIS.Desktop.Editing.TransformByLinkLines" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public TransformByLinkLines()
```
### LinkLines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformByLinkLines.yml" sourcestartlinenumber="1">Gets or sets the link lines to be used for the transformation.</p>


```csharp
public IEnumerable<Polyline> LinkLines { get; set; }
```


