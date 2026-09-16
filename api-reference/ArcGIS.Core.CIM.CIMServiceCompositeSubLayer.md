# CIMServiceCompositeSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Represents a service composite sublayer.</p>


## Object Signature

```csharp
public class CIMServiceCompositeSubLayer : CIMSubLayerBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMServiceCompositeSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Represents a service composite sublayer.</p>


```csharp
public CIMServiceCompositeSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMServiceCompositeSubLayer.</p>


```csharp
public CIMServiceCompositeSubLayer Clone()
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Gets or sets the definition expression. This property is used for composite layers that are backed by feature classes.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMServiceCompositeSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMServiceCompositeSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Gets or sets the composite sublayers.</p>


```csharp
public CIMSubLayerBase[] SubLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMServiceCompositeSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the backing layer. Used when feature layer capabilities are enabled.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


