# CIMglTFMarker3D

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Represents a marker symbol for 3D objects.</p>


## Object Signature

```csharp
public class CIMglTFMarker3D : CIMMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMglTFMarker3D()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Represents a marker symbol for 3D objects.</p>


```csharp
public CIMglTFMarker3D()
```
### AdditionalModelURIs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the URIs of additional binary references used by the model.</p>


```csharp
public string[] AdditionalModelURIs { get; set; }
```
### AnimatedSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the collection of symbol properties that apply when the symbol layer has animation data.</p>


```csharp
public CIMAnimatedSymbolProperties AnimatedSymbolProperties { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Creates a deep copy of CIMglTFMarker3D.</p>


```csharp
public CIMglTFMarker3D Clone()
```
### Depth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the marker depth.</p>


```csharp
public double Depth { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Reconstructs the CIMglTFMarker3D with a specified state from a JSON encoding.</p>


```csharp
public static CIMglTFMarker3D FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsRestricted

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the model can be exported.</p>


```csharp
public bool IsRestricted { get; set; }
```
### ModelURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the GLTF or GLB which contains the node structure.</p>


```csharp
public string ModelURI { get; set; }
```
### PrimitiveShapeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the PrimitiveShapeType.</p>


```csharp
public PrimitiveShapeType PrimitiveShapeType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceStyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets a value indicating the source style name.</p>


```csharp
public string SourceStyleName { get; set; }
```
### SourceSymbolKey

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets a value indicating the source symbol key.</p>


```csharp
public string SourceSymbolKey { get; set; }
```
### Thumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the representative image of the marker as a base64 encoded string.</p>


```csharp
public string Thumbnail { get; set; }
```
### TintColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the color which defines the color that is applied to the marker.</p>


```csharp
public CIMColor TintColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMglTFMarker3D and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseAnchorPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to ignore the marker anchor point and insert the model directly at the data point.</p>


```csharp
public bool UseAnchorPoint { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Gets or sets the marker width.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMglTFMarker3D.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


