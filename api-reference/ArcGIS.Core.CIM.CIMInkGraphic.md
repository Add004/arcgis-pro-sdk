# CIMInkGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Represents an ink graphic.</p>


## Object Signature

```csharp
public class CIMInkGraphic : CIMGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMInkGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Represents an ink graphic.</p>


```csharp
public CIMInkGraphic()
```
### Bounds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Gets or sets the bounds of the ink graphic.</p>


```csharp
public Envelope Bounds { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMInkGraphic.</p>


```csharp
public CIMInkGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMInkGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMInkGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### InkData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Gets or sets the ink data as a string.</p>


```csharp
public string InkData { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RoughSketch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Gets or sets a polyline used to define a rough sketch of the ink data.</p>


```csharp
public Polyline RoughSketch { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMInkGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInkGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


