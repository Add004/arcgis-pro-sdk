# CIMSolidFill

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Represents a solid fill which fills polygonal geometry with a single solid color.</p>


## Object Signature

```csharp
public class CIMSolidFill : CIMFill, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSolidFill()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Represents a solid fill which fills polygonal geometry with a single solid color.</p>


```csharp
public CIMSolidFill()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSolidFill.</p>


```csharp
public CIMSolidFill Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Gets or sets the color that is applied to the fill.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Reconstructs the CIMSolidFill with a specified state from a JSON encoding.</p>


```csharp
public static CIMSolidFill FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSolidFill and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSolidFill.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


