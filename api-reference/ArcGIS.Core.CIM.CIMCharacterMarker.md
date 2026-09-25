# CIMCharacterMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Represents a character marker.</p>


## Object Signature

```csharp
public class CIMCharacterMarker : CIMMarker, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">The shape of a marker is defined by a glyph in a font. The marker is drawn using the specified size and color. Each marker has a defined frame around the glyph that is considered when the size is applied. As a result, character markers of the same size may appear different sizes if the glyphs frames are different sizes.</p>


## Members

### CIMCharacterMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Represents a character marker.</p>


```csharp
public CIMCharacterMarker()
```
### CharacterIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the Unicode decimal value for the individual glyph of the font that defines the shape of the marker.</p>


```csharp
public int CharacterIndex { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCharacterMarker.</p>


```csharp
public CIMCharacterMarker Clone()
```
### Depth3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the depth of the marker when drawn in 3D.</p>


```csharp
public double Depth3D { get; set; }
```
### FontFamilyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the font family name of the font. e.g. Comic Sans.</p>


```csharp
public string FontFamilyName { get; set; }
```
### FontStyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the style name for the font family. e.g. Regular, Bold, or Italic.</p>


```csharp
public string FontStyleName { get; set; }
```
### FontType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the font type.</p>


```csharp
public FontType FontType { get; set; }
```
### FontVariationSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets an array of CIM font variation objects, describing a particular instance of a variable font through the font axis tags and their values. The number of CIM font variations will correspond to the number of variation axes specified by the font. This is only used for variable fonts.</p>


```csharp
public CIMFontVariation[] FontVariationSettings { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Reconstructs the CIMCharacterMarker with a specified state from a JSON encoding.</p>


```csharp
public static CIMCharacterMarker FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RespectFrame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the frame of the character marker should be honored when transforming the marker.</p>


```csharp
public bool RespectFrame { get; set; }
```
### ScaleSymbolsProportionally

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the strokes and/or fills of a marker are scaled proportionally when the symbol size is changed.</p>


```csharp
public bool ScaleSymbolsProportionally { get; set; }
```
### ScaleX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the width of the symbol without changing the height (or depth in 3D), as a ratio.</p>


```csharp
public double ScaleX { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol that is used to renderer the marker.</p>


```csharp
public CIMPolygonSymbol Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCharacterMarker and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalOrientation3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the marker stands a marker upright as though locked in place. The marker can be viewed from all angles.</p>


```csharp
public bool VerticalOrientation3D { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCharacterMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


