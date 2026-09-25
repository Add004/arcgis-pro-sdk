# CIMSolidStroke

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Represents a solid stroke which draws linear geometry with a single solid color.</p>


## Object Signature

```csharp
public class CIMSolidStroke : CIMStroke, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSolidStroke()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Represents a solid stroke which draws linear geometry with a single solid color.</p>


```csharp
public CIMSolidStroke()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSolidStroke.</p>


```csharp
public CIMSolidStroke Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Gets or sets the color that is applied to the stroke.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Reconstructs the CIMSolidStroke with a specified state from a JSON encoding.</p>


```csharp
public static CIMSolidStroke FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSolidStroke and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidStroke.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


