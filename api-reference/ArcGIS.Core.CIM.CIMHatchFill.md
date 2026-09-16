# CIMHatchFill

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Represents a hatch fill which fills polygonal geometry with a uniform series of parallel line symbols.</p>


## Object Signature

```csharp
public class CIMHatchFill : CIMFill, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHatchFill()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Represents a hatch fill which fills polygonal geometry with a uniform series of parallel line symbols.</p>


```csharp
public CIMHatchFill()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHatchFill.</p>


```csharp
public CIMHatchFill Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Reconstructs the CIMHatchFill with a specified state from a JSON encoding.</p>


```csharp
public static CIMHatchFill FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Gets or sets the line symbol that is used to draw the hatch lines in the fill.</p>


```csharp
public CIMLineSymbol LineSymbol { get; set; }
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Gets or sets how much to move the stroke to a new X-position.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Gets or sets how much to move the stroke to a new Y-position.</p>


```csharp
public double OffsetY { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Gets or sets the angle of rotation for all the strokes, in degrees.</p>


```csharp
public double Rotation { get; set; }
```
### Separation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Gets or sets the distance between the line symbols in the hatch pattern.</p>


```csharp
public double Separation { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHatchFill and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHatchFill.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


