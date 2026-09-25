# CIMLinkChartFeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Represents a Link Chart Feature Layer.</p>


## Object Signature

```csharp
public class CIMLinkChartFeatureLayer : CIMGeoFeatureLayerBase, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMLinkChartFeatureLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Represents a Link Chart Feature Layer.</p>


```csharp
public CIMLinkChartFeatureLayer()
```
### AggregationLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the layer URI of the aggregation layer.</p>


```csharp
public string AggregationLayerURI { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartFeatureLayer.</p>


```csharp
public CIMLinkChartFeatureLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartFeatureLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartFeatureLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartFeatureLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFeatureLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


