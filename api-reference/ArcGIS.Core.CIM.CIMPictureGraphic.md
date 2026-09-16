# CIMPictureGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Represents a picture graphic.</p>


## Object Signature

```csharp
public class CIMPictureGraphic : CIMGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPictureGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Represents a picture graphic.</p>


```csharp
public CIMPictureGraphic()
```
### Box

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Gets or sets the bounding box of the picture graphic.</p>


```csharp
[Obsolete("Box is deprecated at 3.4. Use Shape instead.")]
public Envelope Box { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPictureGraphic.</p>


```csharp
public CIMPictureGraphic Clone()
```
### Frame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Gets or sets the graphic frame of the picture graphic.</p>


```csharp
public CIMGraphicFrame Frame { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMPictureGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMPictureGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### PictureURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Gets or sets the URL of the picture graphic. Typically a base64 encoded representation of the picture.</p>


```csharp
public string PictureURL { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the picture data.</p>


```csharp
public string ReferenceURI { get; set; }
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Gets or sets the shape of the picture graphic.</p>


```csharp
public Geometry Shape { get; set; }
```
### SourceURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Gets or sets the source URL of the picture graphic. Typically the source of the image copied into the PictureURL.</p>


```csharp
public string SourceURL { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPictureGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPictureGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


