# CIMTextSymbol

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Represents a text symbol which is used to draw text graphics, bleeds, and annotation. Text symbols do not contain any symbol layers but can have callouts.</p>


## Object Signature

```csharp
public class CIMTextSymbol : CIMSymbol, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTextSymbol()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Represents a text symbol which is used to draw text graphics, bleeds, and annotation. Text symbols do not contain any symbol layers but can have callouts.</p>


```csharp
public CIMTextSymbol()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the amount of rotation applied to the text symbol, measured in degrees, around the geometry.</p>


```csharp
public double Angle { get; set; }
```
### AngleX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the amount of rotation of the text symbol around the X axis, measured in degrees, around the geometry. This type of rotation is also referred to as tilt. It is applied in 3D.</p>


```csharp
public double AngleX { get; set; }
```
### AngleY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the amount of rotation of the text symbol around the Y axis, measured in degrees, around the geometry. This type of rotation is also referred to as roll. It is applied in 3D.</p>


```csharp
public double AngleY { get; set; }
```
### BillboardMode3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the billboard mode of the text symbol.</p>


```csharp
public BillboardMode BillboardMode3D { get; set; }
```
### BlockProgression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the direction in which multi-line text is stacked.</p>


```csharp
public BlockProgression BlockProgression { get; set; }
```
### Callout

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the callout or background of the text with optional leader lines.</p>


```csharp
public CIMCallout Callout { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTextSymbol.</p>


```csharp
public CIMTextSymbol Clone()
```
### CompatibilityMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the text in a fashion compatible with ArcMap.</p>


```csharp
public bool CompatibilityMode { get; set; }
```
### CountryISO

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the ISO code for the base country of the text.</p>


```csharp
public string CountryISO { get; set; }
```
### Depth3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the depth of the glyph when drawn in 3D. This is an extrusion of the characters of the text in the Z axis.</p>


```csharp
public double Depth3D { get; set; }
```
### DrawGlyphsAsGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether fonts that are drawn as rasters at some scales to draw as vectors instead.</p>


```csharp
public bool DrawGlyphsAsGeometry { get; set; }
```
### DrawSoftHyphen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether soft hyphens should be drawn. Soft hyphens are invisible markers that indicate where a hyphenated break is allowed within the text. They are only drawn if there is word wrapping at the end of a line.</p>


```csharp
public bool DrawSoftHyphen { get; set; }
```
### ExtrapolateBaselines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the baseline of the text geometry should be expanded in the same manner as the existing geometry if the text extends beyond the baseline.</p>


```csharp
public bool ExtrapolateBaselines { get; set; }
```
### FlipAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the angle (in degrees from vertical) at which point rotated text is flipped (mirrored) in place.</p>


```csharp
public double FlipAngle { get; set; }
```
### FontEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets whether the text is drawn as subscript or superscript.</p>


```csharp
public FontEffects FontEffects { get; set; }
```
### FontEncoding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the font encoding.</p>


```csharp
public FontEncoding FontEncoding { get; set; }
```
### FontFamilyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the font family name of the font. e.g. Comic Sans.</p>


```csharp
public string FontFamilyName { get; set; }
```
### FontStyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the style name for the font family. e.g. Regular, Bold, or Italic.</p>


```csharp
public string FontStyleName { get; set; }
```
### FontType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the type of font that the font family/style name reference.</p>


```csharp
public FontType FontType { get; set; }
```
### FontVariationSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets an array of CIM font variation objects, describing a particular instance of a variable font through the font axis tags and their values. The number of CIM font variations will correspond to the number of variation axes specified by the font. This is only used for variable fonts.</p>


```csharp
public CIMFontVariation[] FontVariationSettings { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Reconstructs the CIMTextSymbol with a specified state from a JSON encoding.</p>


```csharp
public static CIMTextSymbol FromJson(string json, JsonDeserializationSettings settings = null)
```
### GlyphRotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets an additional rotation that is applied to the individual glyphs contained in the text. This is applied to the individual glyphs whereas Angle, AngleX and AngleY are affect how the entire text string is oriented.</p>


```csharp
public double GlyphRotation { get; set; }
```
### HaloSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the size of the halo that extends beyond the symbol shape.</p>


```csharp
public double HaloSize { get; set; }
```
### HaloSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol that is used to draw the halo for a text symbol.</p>


```csharp
public CIMPolygonSymbol HaloSymbol { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the size of the text in points.</p>


```csharp
public double Height { get; set; }
```
### Hinting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets if hinting from the font is used for text rendering. Hinting is information included with most fonts to effectively fit the vector glyphs of the font into the raster grid onto which they are displayed.</p>


```csharp
public GlyphHinting Hinting { get; set; }
```
### HorizontalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the alignment type used to align the text to the geometry horizontally. Affects which side of a point geometry the point text is drawn or which end of a line it is drawn close to. Commonly used to define how stacked text appears.</p>


```csharp
public HorizontalAlignment HorizontalAlignment { get; set; }
```
### IndentAfter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets how many points to indent the text back from the end of the baseline.</p>


```csharp
public double IndentAfter { get; set; }
```
### IndentBefore

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets how many points to indent the text from the beginning of the baseline.</p>


```csharp
public double IndentBefore { get; set; }
```
### IndentFirstLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets how many points to indent the text from the beginning of the baseline for the first line only.</p>


```csharp
public double IndentFirstLine { get; set; }
```
### Kerning

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text is drawn with metric kerning, which adjusts the spacing between individual letter forms.</p>


```csharp
public bool Kerning { get; set; }
```
### LanguageISO

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets whether the ISO code for the base language of the text.</p>


```csharp
public string LanguageISO { get; set; }
```
### LetterSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the additional spacing that is added to each glyph beyond what is defined by its character box in the font. Value indicates the percentage of a glyph's width. Also known as tracking.</p>


```csharp
public double LetterSpacing { get; set; }
```
### LetterWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the width that is added to each glyph beyond what is defined by its character box in its font. This is a percentage of the original glyph.</p>


```csharp
public double LetterWidth { get; set; }
```
### Ligatures

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether text is to be drawn with ligatures, which occur when two or more letters or portions of letters are joined to form a single glyph.</p>


```csharp
public bool Ligatures { get; set; }
```
### LineGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the spacing between lines of text. This is also known as leading or line spacing.</p>


```csharp
public double LineGap { get; set; }
```
### LineGapType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the type of line gap that is applied.</p>


```csharp
public LineGapType LineGapType { get; set; }
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the X offset.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the Y offset.</p>


```csharp
public double OffsetY { get; set; }
```
### OffsetZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the Z offset.</p>


```csharp
public double OffsetZ { get; set; }
```
### Overprint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the symbol should overprint in press printing.</p>


```csharp
public bool Overprint { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShadowColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the color of the shadow that is defined for the text symbol. The shadow is drawn as an offset copy of the text.</p>


```csharp
public CIMColor ShadowColor { get; set; }
```
### ShadowOffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the shadow offset from the text symbol in the horizontal direction. If X and Y are zero, no shadow is drawn.</p>


```csharp
public double ShadowOffsetX { get; set; }
```
### ShadowOffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the shadow offset from the text symbol in the vertical direction. If X and Y are zero, no shadow is drawn.</p>


```csharp
public double ShadowOffsetY { get; set; }
```
### SmallCaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text should be drawn as Small Capitals, where lower case text is converted to small caps and upper case text is left as upper case.</p>


```csharp
public bool SmallCaps { get; set; }
```
### Strikethrough

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the text with a strike through it.</p>


```csharp
public bool Strikethrough { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol that is used to draw the glyphs of the text.</p>


```csharp
public CIMPolygonSymbol Symbol { get; set; }
```
### Symbol3DProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the collection of properties that are applied to the text symbol only in a 3D context.</p>


```csharp
public CIM3DSymbolProperties Symbol3DProperties { get; set; }
```
### TextCase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the letter case used to draw the text.</p>


```csharp
public TextCase TextCase { get; set; }
```
### TextDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the base text direction to draw the text.</p>


```csharp
public TextReadingDirection TextDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTextSymbol and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Underline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the text with an underline.</p>


```csharp
public bool Underline { get; set; }
```
### VerticalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the vertical alignment of the text.</p>


```csharp
public VerticalAlignment VerticalAlignment { get; set; }
```
### VerticalGlyphOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the orientation for the non-vertical text in a vertical layout. For example, an English fragment in a Japanese text.</p>


```csharp
public VerticalGlyphOrientation VerticalGlyphOrientation { get; set; }
```
### VerticalPositioning

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the vertical position of the text within its frame.</p>


```csharp
public VerticalPositioning VerticalPositioning { get; set; }
```
### WordSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Gets or sets the additional spacing that is added to between the words of the text string. 100% indicates that regular spacing is used.</p>


```csharp
public double WordSpacing { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextSymbol.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


