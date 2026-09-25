# CIMMultipointGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Represents a shape graphic with a Multipoint geometry.</p>


## Object Signature

```csharp
public class CIMMultipointGraphic : CIMShapeGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultipointGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Represents a shape graphic with a Multipoint geometry.</p>


```csharp
public CIMMultipointGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultipointGraphic.</p>


```csharp
public CIMMultipointGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMMultipointGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultipointGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Multipoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Gets or sets the graphic's multipoint geometry.</p>


```csharp
public Multipoint Multipoint { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultipointGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipointGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


