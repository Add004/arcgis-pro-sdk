# CIMNitfLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Represents a NITF composite layer.</p>


## Object Signature

```csharp
public class CIMNitfLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNitfLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Represents a NITF composite layer.</p>


```csharp
public CIMNitfLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNitfLayer.</p>


```csharp
public CIMNitfLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection for the raster this layer is based on.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### ExtraItems

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Gets or sets the names of the layers (and tables) not visible by default.</p>


```csharp
public string[] ExtraItems { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMNitfLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNitfLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Gets or sets the layer URIs of the layers in the NITF layer.</p>


```csharp
public string[] Layers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNitfLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


