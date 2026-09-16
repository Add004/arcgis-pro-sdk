# CIMPictureFill

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Represents a picture fill which fills polygonal geometry with a picture. Supported file types are .bmp, .jpg, .png, and .gif.</p>


## Object Signature

```csharp
public class CIMPictureFill : CIMFill, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPictureFill()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Represents a picture fill which fills polygonal geometry with a picture. Supported file types are .bmp, .jpg, .png, and .gif.</p>


```csharp
public CIMPictureFill()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPictureFill.</p>


```csharp
public CIMPictureFill Clone()
```
### ColorSubstitutions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the color substitutions which allows colors in the image to be substituted with a different color.</p>


```csharp
public CIMColorSubstitution[] ColorSubstitutions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Reconstructs the CIMPictureFill with a specified state from a JSON encoding.</p>


```csharp
public static CIMPictureFill FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the height of the image.</p>


```csharp
public double Height { get; set; }
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the distance that the image is offset in the horizontal direction.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the distance that the image is offset in the vertical direction.</p>


```csharp
public double OffsetY { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets angle of the image within the fill.</p>


```csharp
public double Rotation { get; set; }
```
### ScaleX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the width of the symbol without changing the height (or depth in 3D), as a ratio.</p>


```csharp
public double ScaleX { get; set; }
```
### TextureFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets how the image is resampled.</p>


```csharp
public TextureFilter TextureFilter { get; set; }
```
### TintColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the color that is applied as a tint to the image. The color is applied to the whole image. When the tint is set to white the image appears with its native colors.</p>


```csharp
public CIMColor TintColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPictureFill and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Gets or sets the URL of the image. Typically a base64 encoded image.</p>


```csharp
public string URL { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureFill.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


