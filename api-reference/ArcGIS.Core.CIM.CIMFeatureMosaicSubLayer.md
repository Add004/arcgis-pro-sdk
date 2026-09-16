# CIMFeatureMosaicSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Represents mosaic feature sub layer.</p>


## Object Signature

```csharp
public class CIMFeatureMosaicSubLayer : CIMFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMFeatureMosaicSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Represents mosaic feature sub layer.</p>


```csharp
public CIMFeatureMosaicSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFeatureMosaicSubLayer.</p>


```csharp
public CIMFeatureMosaicSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMFeatureMosaicSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMFeatureMosaicSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### MosaicSubLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Gets or sets the mosaic sublayer type.</p>


```csharp
public MosaicSubLayerType MosaicSubLayerType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFeatureMosaicSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureMosaicSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


