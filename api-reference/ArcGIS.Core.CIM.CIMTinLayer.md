# CIMTinLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Represents a TIN layer which displays TIN data sources, a data structure that represents terrain data as a triangulated irregular network.</p>


## Object Signature

```csharp
public class CIMTinLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Represents a TIN layer which displays TIN data sources, a data structure that represents terrain data as a triangulated irregular network.</p>


```csharp
public CIMTinLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTinLayer.</p>


```csharp
public CIMTinLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Gets or sets the display field.</p>


```csharp
public string DisplayField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTinLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTinLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Gets or sets the renderers.</p>


```csharp
public CIMTinRenderer[] Renderers { get; set; }
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to scale symbols.</p>


```csharp
public bool ScaleSymbols { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTinLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


