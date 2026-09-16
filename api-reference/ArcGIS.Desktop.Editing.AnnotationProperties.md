# AnnotationProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Provides access to the attributes of annotation features.</p>


## Object Signature

```csharp
public sealed class AnnotationProperties
```


## Members

### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the amount of rotation applied to the annotation around the geometry. This is only valid for point and two point polyline geometries.  Measured in degrees.</p>


```csharp
public double? Angle { get; set; }
```
### CharacterSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the character spacing.</p>


```csharp
public double? CharacterSpacing { get; set; }
```
### CharacterWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the character width.</p>


```csharp
public double? CharacterWidth { get; set; }
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the color.</p>


```csharp
public CIMColor Color { get; set; }
```
### FlipAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Specifies the angle, in degrees from the vertical, at which point rotated text is flipped, or mirrored, in place. At this point the text starting point becomes the ending point and conversly.</p>


```csharp
public double? FlipAngle { get; set; }
```
### FontEffects

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets whether the annotation is drawn as subscript or superscript.</p>


```csharp
public FontEffects? FontEffects { get; set; }
```
### FontName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the family name of the font.  e.g. Comic Sans.</p>


```csharp
public string FontName { get; set; }
```
### FontSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the font size.</p>


```csharp
public double? FontSize { get; set; }
```
### FontStyle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the style name for the font family.  e.g. Regular, Bold or Italic.</p>


```csharp
public string FontStyle { get; set; }
```
### FontType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the type of font that the font family/style name reference.</p>


```csharp
public FontType? FontType { get; set; }
```
### FontVariationSettings

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the values that determine how the variable font displays.</p>


```csharp
public CIMFontVariation[] FontVariationSettings { get; set; }
```
### HorizontalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the horizontal alignment type used to align the text to the geometry. Affects which side of a point geometry the text is drawn or which end of a line it is drawn close to.
Commonly used to define how stacked text appears.</p>


```csharp
public HorizontalAlignment? HorizontalAlignment { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.Layer" data-throw-if-not-resolved="false"></xref> of the annotation feature.</p>


```csharp
public Layer Layer { get; }
```
### LoadFromTextGraphic(CIMTextGraphic)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Loads the specified text graphic into the annotation properties.</p>


```csharp
public void LoadFromTextGraphic(CIMTextGraphic textGraphic)
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the X offset.</p>


```csharp
public double? OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the Y offset.</p>


```csharp
public double? OffsetY { get; set; }
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the text baseline shape.</p>


```csharp
public Geometry Shape { get; set; }
```
### SmallCaps

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets whether the annotation should be drawn as Small Capitals; where lower case is converted to small caps and upper case text is left as upper case.</p>


```csharp
public bool? SmallCaps { get; set; }
```
### SymbolID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the symbolID. To set the symbolID, this method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long? SymbolID { get; set; }
```
### TextCase

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the letter case used to draw the annotation.</p>


```csharp
public TextCase? TextCase { get; set; }
```
### TextGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMTextGraphic" data-throw-if-not-resolved="false"></xref> representation of the annotation.</p>


```csharp
public CIMTextGraphic TextGraphic { get; }
```
### TextString

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the annotation text string.</p>


```csharp
public string TextString { get; set; }
```
### Underline

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets whether to draw the annotation with an underline.</p>


```csharp
public bool? Underline { get; set; }
```
### VerticalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the vertical alignment of the annotation.</p>


```csharp
public VerticalAlignment? VerticalAlignment { get; set; }
```
### WordSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.AnnotationProperties.yml" sourcestartlinenumber="1">Gets and sets the additional spacing that is added between the words of the text string. 100% indicates that regular spacing is used.</p>


```csharp
public double? WordSpacing { get; set; }
```


