# CIMPictureMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Represents a picture marker created from a raster (bitmapped) image file. The image can have color substitutions to replace one or more colors in the image or it can have a tint applied to the whole image depending on the picture type. Supported formats are .bmp, .jpg, .png, and .gif.</p>


## Object Signature

```csharp
public class CIMPictureMarker : CIMMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPictureMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Represents a picture marker created from a raster (bitmapped) image file. The image can have color substitutions to replace one or more colors in the image or it can have a tint applied to the whole image depending on the picture type. Supported formats are .bmp, .jpg, .png, and .gif.</p>


```csharp
public CIMPictureMarker()
```
### AnimatedSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets the collection of symbol properties that apply when the symbol layer has animation data.</p>


```csharp
public CIMAnimatedSymbolProperties AnimatedSymbolProperties { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPictureMarker.</p>


```csharp
public CIMPictureMarker Clone()
```
### ColorSubstitutions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets the color substitutions for the picture.</p>


```csharp
public CIMColorSubstitution[] ColorSubstitutions { get; set; }
```
### Depth3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets the depth of the image when drawn in 3D.</p>


```csharp
public double Depth3D { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Reconstructs the CIMPictureMarker with a specified state from a JSON encoding.</p>


```csharp
public static CIMPictureMarker FromJson(string json, JsonDeserializationSettings settings = null)
```
### InvertBackfaceTexture

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the image is right-reading when viewed from behind.</p>


```csharp
public bool InvertBackfaceTexture { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets the scale X which changes the width of the symbol without changing the height (or depth in 3D), as a ratio.</p>


```csharp
public double ScaleX { get; set; }
```
### TextureFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets how the image is resampled.</p>


```csharp
public TextureFilter TextureFilter { get; set; }
```
### TintColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets the color that is applied as a tint to the image. The color is applied to the whole image. When the tint is set to white the image appears with its native colors.</p>


```csharp
public CIMColor TintColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPictureMarker and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets the image that is used in the symbol layer. Typically a base64 encoded image.</p>


```csharp
public string URL { get; set; }
```
### VerticalOrientation3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the marker stands upright as though locked in place. The marker can be viewed from all angles.</p>


```csharp
public bool VerticalOrientation3D { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


