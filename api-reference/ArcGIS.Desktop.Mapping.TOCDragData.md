# TOCDragData

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCDragData.yml" sourcestartlinenumber="1">Provides access to map member content dragged off the TOC.</p>


## Object Signature

```csharp
public interface TOCDragData
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCDragData.yml" sourcestartlinenumber="1">The public API only supports retrieving drag data for the TOC
within the same Pro process. Check <xref href="ArcGIS.Desktop.Mapping.TOCDragData.InProcess" data-throw-if-not-resolved="false"></xref> to determine if the
drag was initiated within the same Pro process or not.</p>


## Members

### DraggedContent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCDragData.yml" sourcestartlinenumber="1">Gets the map member content being dragged.</p>


```csharp
IReadOnlyList<MapMember> DraggedContent { get; }
```
### InProcess

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCDragData.yml" sourcestartlinenumber="1">Gets whether the drag was initiated within the current Pro process.</p>


```csharp
bool InProcess { get; }
```
### SourceMapURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TOCDragData.yml" sourcestartlinenumber="1">Gets the source URI of the map whose TOC is the drag source.</p>


```csharp
string SourceMapURI { get; }
```


