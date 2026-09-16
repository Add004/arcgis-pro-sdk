# CIMOrientedImageryLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Represents an oriented imagery layer.</p>


## Object Signature

```csharp
public class CIMOrientedImageryLayer : CIMGeoFeatureLayerBase, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMOrientedImageryLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Represents an oriented imagery layer.</p>


```csharp
public CIMOrientedImageryLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOrientedImageryLayer.</p>


```csharp
public CIMOrientedImageryLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMOrientedImageryLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMOrientedImageryLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ImageAccessConnections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Gets or sets the collection of image access objects, which provide information on how to access the images in the oriented imagery dataset.</p>


```csharp
public CIMOrientedImageryImageAccessConnections[] ImageAccessConnections { get; set; }
```
### OrientedImageryPropertyOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Gets or sets the overrides for editable properties of the oriented imagery dataset on the layer.</p>


```csharp
public IDictionary<string, object> OrientedImageryPropertyOverrides { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOrientedImageryLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


