# CIMPolygonGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Represents a polygon graphic.</p>


## Object Signature

```csharp
public class CIMPolygonGraphic : CIMShapeGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPolygonGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Represents a polygon graphic.</p>


```csharp
public CIMPolygonGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPolygonGraphic.</p>


```csharp
public CIMPolygonGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMPolygonGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMPolygonGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Polygon

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Gets or sets the polygon of the polygon graphic.</p>


```csharp
public Polygon Polygon { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPolygonGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


