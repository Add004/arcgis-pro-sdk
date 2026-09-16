# CIMDimensionLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Represents an dimension layer used to draw dimension feature classes.</p>


## Object Signature

```csharp
public class CIMDimensionLayer : CIMBasicFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMDimensionLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Represents an dimension layer used to draw dimension feature classes.</p>


```csharp
public CIMDimensionLayer()
```
### BarrierWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Gets or sets the weight of features in this layer when considered as barriers to labeling.</p>


```csharp
public BarrierWeight BarrierWeight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDimensionLayer.</p>


```csharp
public CIMDimensionLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMDimensionLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMDimensionLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not geometries are snappable.</p>


```csharp
public bool Snappable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDimensionLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


