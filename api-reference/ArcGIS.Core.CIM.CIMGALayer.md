# CIMGALayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Represents the GA layer.</p>


## Object Signature

```csharp
public class CIMGALayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGALayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Represents the GA layer.</p>


```csharp
public CIMGALayer()
```
### AOI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Gets or sets the area of interest.</p>


```csharp
public Envelope AOI { get; set; }
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Gets or sets the name of the active range.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGALayer.</p>


```csharp
public CIMGALayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Reconstructs the CIMGALayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGALayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsFlattened

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is flattened.</p>


```csharp
public bool IsFlattened { get; set; }
```
### Method

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Gets or sets the GA method.</p>


```csharp
public CIMGAMethod Method { get; set; }
```
### RangeDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Gets or sets the range definitions.</p>


```csharp
public CIMRangeDefinition[] RangeDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Gets or sets the renderers.</p>


```csharp
public CIMRenderer[] Renderers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGALayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGALayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


