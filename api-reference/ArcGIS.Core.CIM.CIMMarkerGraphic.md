# CIMMarkerGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Represents a marker graphic which is used to define vector graphics in a vector marker.</p>


## Object Signature

```csharp
public class CIMMarkerGraphic : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Represents a marker graphic which is used to define vector graphics in a vector marker.</p>


```csharp
public CIMMarkerGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerGraphic.</p>


```csharp
public CIMMarkerGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Gets or sets the geometry of the marker.</p>


```csharp
public Geometry Geometry { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the marker graphic, can be a point, line, polygon, or text symbol.</p>


```csharp
public CIMSymbol Symbol { get; set; }
```
### TextString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Gets or sets the text that is defined within the marker if drawn with a text symbol.</p>


```csharp
public string TextString { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


