# CIMSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Represents sublayer.</p>


## Object Signature

```csharp
public class CIMSubLayer : CIMSubLayerBase, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Defines a sublayer for a containing parent layer. The parent layer is a full-fledged layer, and it controls the sublayer, which is subordinate to the parent. The sublayer is not a layer definition itself rather, it is a property of its parent layer.</p>


## Members

### CIMSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Represents sublayer.</p>


```csharp
public CIMSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSubLayer.</p>


```csharp
public CIMSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


