# CIMLineGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Represents a line graphic.</p>


## Object Signature

```csharp
public class CIMLineGraphic : CIMShapeGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLineGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Represents a line graphic.</p>


```csharp
public CIMLineGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLineGraphic.</p>


```csharp
public CIMLineGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMLineGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMLineGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Line

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Gets or sets the polyline of the line graphic.</p>


```csharp
public Polyline Line { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLineGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


