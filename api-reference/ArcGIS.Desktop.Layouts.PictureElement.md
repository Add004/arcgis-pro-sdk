# PictureElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.PictureElement.yml" sourcestartlinenumber="1">Represents a picture element on a page layout.</p>


## Object Signature

```csharp
public class PictureElement : GraphicElement, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.PictureElement.yml" sourcestartlinenumber="1">A PictureElement is a type of <xref href="ArcGIS.Desktop.Layouts.GraphicElement?text=GraphicElement" data-throw-if-not-resolved="false"></xref> and therefore can be positioned or resized on the page.
Picture elements are embedded in the project file (.aprx) but the <xref href="ArcGIS.Desktop.Layouts.PictureElement.SourcePath?text=SourcePath" data-throw-if-not-resolved="false"></xref> property will
return the original source file source path. You can change the picture by using the <xref href="ArcGIS.Desktop.Layouts.PictureElement.SetSourcePath?text=SetSourcePath" data-throw-if-not-resolved="false"></xref>
method along with a new file path.</p>


## Members

### SetSourcePath(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.PictureElement.yml" sourcestartlinenumber="1">Regenerates the picture using the new file path to a picture on disk. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetSourcePath(string URI)
```
### SourcePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.PictureElement.yml" sourcestartlinenumber="1">Gets the file path of where the picture was added from.</p>


```csharp
public string SourcePath { get; }
```


