# CIMTopologyLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Represents a topology dataset as a layer and draws its errors,
exceptions, and areas in need of validation.</p>


## Object Signature

```csharp
public class CIMTopologyLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTopologyLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Represents a topology dataset as a layer and draws its errors,
exceptions, and areas in need of validation.</p>


```csharp
public CIMTopologyLayer()
```
### AllLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Gets or sets the paths of the layers in the topology layer.</p>


```csharp
public string[] AllLayers { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTopologyLayer.</p>


```csharp
public CIMTopologyLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTopologyLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTopologyLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTopologyLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TopologyConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Gets or sets the topology data connection.</p>


```csharp
public CIMDataConnection TopologyConnection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopologyLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


