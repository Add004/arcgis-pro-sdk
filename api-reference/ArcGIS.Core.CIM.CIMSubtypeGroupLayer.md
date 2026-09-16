# CIMSubtypeGroupLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Represents a subtype group layer that works with feature classes enabled with subtypes.</p>


## Object Signature

```csharp
public class CIMSubtypeGroupLayer : CIMBasicFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">A subtype layer is a group layer that contains feature layers, each of which represents a subtype in a feature class.</p>


## Members

### CIMSubtypeGroupLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Represents a subtype group layer that works with feature classes enabled with subtypes.</p>


```csharp
public CIMSubtypeGroupLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSubtypeGroupLayer.</p>


```csharp
public CIMSubtypeGroupLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMSubtypeGroupLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMSubtypeGroupLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubtypeLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Gets or sets the layer URI corresponding to each subtype value.</p>


```csharp
public string[] SubtypeLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSubtypeGroupLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


