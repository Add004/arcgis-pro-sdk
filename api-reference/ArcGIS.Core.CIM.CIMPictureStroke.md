# CIMPictureStroke

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Represents a picture stroke which draws linear geometry with a repeating image file. Supported file types are .bmp, .jpg, .png, and .gif.</p>


## Object Signature

```csharp
public class CIMPictureStroke : CIMStroke, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPictureStroke()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Represents a picture stroke which draws linear geometry with a repeating image file. Supported file types are .bmp, .jpg, .png, and .gif.</p>


```csharp
public CIMPictureStroke()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPictureStroke.</p>


```csharp
public CIMPictureStroke Clone()
```
### ColorSubstitutions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Gets or sets the color substitutions for the picture.</p>


```csharp
public CIMColorSubstitution[] ColorSubstitutions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Reconstructs the CIMPictureStroke with a specified state from a JSON encoding.</p>


```csharp
public static CIMPictureStroke FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextureFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Gets or sets how the image is resampled.</p>


```csharp
public TextureFilter TextureFilter { get; set; }
```
### TintColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Gets or sets the color that is applied as a tint to the image. The color is applied to the whole image. When the tint is set to white the image appears with its native colors.</p>


```csharp
public CIMColor TintColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPictureStroke and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Gets or sets the image that is used in the symbol layer. Typically a base64 encoded image.</p>


```csharp
public string URL { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureStroke.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


