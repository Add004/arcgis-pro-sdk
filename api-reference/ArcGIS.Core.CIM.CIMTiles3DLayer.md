# CIMTiles3DLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Represents a 3D Tiles layer.</p>


## Object Signature

```csharp
public class CIMTiles3DLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTiles3DLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Represents a 3D Tiles layer.</p>


```csharp
public CIMTiles3DLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTiles3DLayer.</p>


```csharp
public CIMTiles3DLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTiles3DLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTiles3DLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ModificationLayerEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the modification is enabled.</p>


```csharp
public bool ModificationLayerEnabled { get; set; }
```
### ModificationLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the modification layer.</p>


```csharp
public string ModificationLayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the geometries are snappable.</p>


```csharp
public bool Snappable { get; set; }
```
### Tiles3DLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Gets or sets the 3D Tiles layer type. Typically set by the system and should not be modified.</p>


```csharp
public Tiles3DLayerType Tiles3DLayerType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTiles3DLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiles3DLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


