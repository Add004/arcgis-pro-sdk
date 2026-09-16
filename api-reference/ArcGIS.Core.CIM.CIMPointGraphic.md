# CIMPointGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Represents a point graphic.</p>


## Object Signature

```csharp
public class CIMPointGraphic : CIMShapeGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Represents a point graphic.</p>


```csharp
public CIMPointGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointGraphic.</p>


```csharp
public CIMPointGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMPointGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Leaders

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Gets or sets a collection of leaders coming off of the graphic.</p>


```csharp
public CIMLeader[] Leaders { get; set; }
```
### Location

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Gets or sets the location of the point graphic.</p>


```csharp
public MapPoint Location { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


