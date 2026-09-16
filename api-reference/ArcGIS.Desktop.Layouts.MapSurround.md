# MapSurround

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSurround.yml" sourcestartlinenumber="1">Represents a map surround on a page layout.</p>


## Object Signature

```csharp
public class MapSurround : Element, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable
```

## Remarks

<p>
    A MapSurround is a type of <xref href="ArcGIS.Desktop.Layouts.Element" data-throw-if-not-resolved="false"></xref> and therefore can be positioned or resized on the page.  A MapSurround also has an 
    associated <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref> that can be modified.
    </p>
<p>
  <xref href="ArcGIS.Desktop.Layouts.Legend?text=Legend" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.NorthArrow?text=NorthArrow" data-throw-if-not-resolved="false"></xref>, and
    <xref href="ArcGIS.Desktop.Layouts.ScaleBar?text=ScaleBar" data-throw-if-not-resolved="false"></xref> are types of a MapSurround.
    </p>


## Members

### MapFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSurround.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref> associated with the MapSurround.</p>


```csharp
public MapFrame MapFrame { get; }
```
### SetMapFrame(MapFrame)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSurround.yml" sourcestartlinenumber="1">Sets a <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame+" data-throw-if-not-resolved="false"></xref> to the MapSurround.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetMapFrame(MapFrame mapFrame)
```


