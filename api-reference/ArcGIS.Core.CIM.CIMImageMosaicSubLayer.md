# CIMImageMosaicSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Represents an image mosaic sublayer.</p>


## Object Signature

```csharp
public class CIMImageMosaicSubLayer : CIMImageServiceLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMImageMosaicSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Represents an image mosaic sublayer.</p>


```csharp
public CIMImageMosaicSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMImageMosaicSubLayer.</p>


```csharp
public CIMImageMosaicSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMImageMosaicSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMImageMosaicSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### MosaicSubLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Gets or sets the mosaic sublayer type.</p>


```csharp
public MosaicSubLayerType MosaicSubLayerType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMImageMosaicSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMosaicSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


