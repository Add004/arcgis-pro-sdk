# CIMViewCamera

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Represents a view camera.</p>


## Object Signature

```csharp
public class CIMViewCamera : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMViewCamera()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Represents a view camera.</p>


```csharp
public CIMViewCamera()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Creates a deep copy of CIMViewCamera.</p>


```csharp
public CIMViewCamera Clone()
```
### FieldOfView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the camera's field-of-view in degrees.</p>


```csharp
public double FieldOfView { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Reconstructs the CIMViewCamera with a specified state from a JSON encoding.</p>


```csharp
public static CIMViewCamera FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public double Heading { get; set; }
```
### Pitch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the pitch.</p>


```csharp
public double Pitch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Roll

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the roll.</p>


```csharp
public double Roll { get; set; }
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the scale.</p>


```csharp
public double Scale { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMViewCamera and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ViewportHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the height of the viewport in meters. Viewport height and width are used for consistent camera positioning in isometric 3D views, eye separation in 3D stereo views and defines the focal distance in perspective views.</p>


```csharp
public double ViewportHeight { get; set; }
```
### ViewportWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets the width of the viewport in meters. Viewport height and width are used for consistent camera positioning in isometric 3D views, eye separation in 3D stereo views and defines the focal distance in perspective views.</p>


```csharp
public double ViewportWidth { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets X.</p>


```csharp
public double X { get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets Y.</p>


```csharp
public double Y { get; set; }
```
### Z

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewCamera.yml" sourcestartlinenumber="1">Gets or sets Z.</p>


```csharp
public double Z { get; set; }
```


