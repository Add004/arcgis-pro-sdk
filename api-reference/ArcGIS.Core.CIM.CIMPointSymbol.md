# CIMPointSymbol

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Represents a point symbol used to draw point features and point graphics.</p>


## Object Signature

```csharp
public class CIMPointSymbol : CIMMultiLayerSymbol, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointSymbol()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Represents a point symbol used to draw point features and point graphics.</p>


```csharp
public CIMPointSymbol()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the amount of variation applied to the symbol, measured in degrees, propagated cumulatively to all marker symbols.</p>


```csharp
public double Angle { get; set; }
```
### AngleAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets whether point symbols align to the map or to the display when a rotation is applied to the map.</p>


```csharp
public AngleAlignment AngleAlignment { get; set; }
```
### Callout

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the callout of the point symbol.</p>


```csharp
public CIMCallout Callout { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointSymbol.</p>


```csharp
public CIMPointSymbol Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Reconstructs the CIMPointSymbol with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointSymbol FromJson(string json, JsonDeserializationSettings settings = null)
```
### HaloSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the size of the halo that extends beyond the symbol shape.</p>


```csharp
public double HaloSize { get; set; }
```
### HaloSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol that is used to draw the halo for a point symbol.</p>


```csharp
public CIMPolygonSymbol HaloSymbol { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the X scale which changes the width of the symbol without changing the height (or depth in 3D), as a ratio.</p>


```csharp
public double ScaleX { get; set; }
```
### Symbol3DProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Gets or sets the collection of symbol properties that apply when the symbol is used in a 3D context.</p>


```csharp
public CIM3DSymbolProperties Symbol3DProperties { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointSymbol and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbol.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


