# CIMGaussianSplatLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Represents a Gaussian Splat layer.</p>


## Object Signature

```csharp
public class CIMGaussianSplatLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGaussianSplatLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Represents a Gaussian Splat layer.</p>


```csharp
public CIMGaussianSplatLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGaussianSplatLayer.</p>


```csharp
public CIMGaussianSplatLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMGaussianSplatLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGaussianSplatLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the geometries are snappable.</p>


```csharp
public bool Snappable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGaussianSplatLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGaussianSplatLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


