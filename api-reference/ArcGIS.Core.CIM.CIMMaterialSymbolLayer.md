# CIMMaterialSymbolLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Represents a material which defines how the multipatch or mesh is drawn.</p>


## Object Signature

```csharp
public class CIMMaterialSymbolLayer : CIMSymbolLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaterialSymbolLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Represents a material which defines how the multipatch or mesh is drawn.</p>


```csharp
public CIMMaterialSymbolLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaterialSymbolLayer.</p>


```csharp
public CIMMaterialSymbolLayer Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the material color.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMMaterialSymbolLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaterialSymbolLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaterialMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the mode in which the material is applied.</p>


```csharp
public MaterialMode MaterialMode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaterialSymbolLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterialSymbolLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


