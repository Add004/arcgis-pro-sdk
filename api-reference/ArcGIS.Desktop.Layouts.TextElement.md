# TextElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextElement.yml" sourcestartlinenumber="1">Represents a text element on a page layout.</p>


## Object Signature

```csharp
public class TextElement : GraphicElement, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextElement.yml" sourcestartlinenumber="1">The TextElement class represents text elements on a page layout.  This includes items such as inserted point text, rectangle text, and so on. It can
also include text elements that are part of a group element but it does not include text that is part of a legend, scale bar or other map surround items.</p>


## Members

### SetTagType(TextTagType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextElement.yml" sourcestartlinenumber="1">Sets the accessibility tag type for the text element when exporting to an accessible PDF. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetTagType(TextTagType tagType)
```
### SetTextProperties(TextProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextElement.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Desktop.Layouts.TextProperties?text=TextProperties" data-throw-if-not-resolved="false"></xref> for a TextElement. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetTextProperties(TextProperties textProperties)
```
### TagType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextElement.yml" sourcestartlinenumber="1">Gets the accessibility tag type used for the text element when exporting to an accessible PDF.</p>


```csharp
public TextTagType TagType { get; }
```
### TextProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextElement.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Layouts.TextProperties?text=TextProperties" data-throw-if-not-resolved="false"></xref> for a text element.</p>


```csharp
public TextProperties TextProperties { get; }
```


