# CIMChartTrajectoryProfileLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Represents the layer to be used as an additional input.</p>


## Object Signature

```csharp
public class CIMChartTrajectoryProfileLayer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartTrajectoryProfileLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Represents the layer to be used as an additional input.</p>


```csharp
public CIMChartTrajectoryProfileLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartTrajectoryProfileLayer.</p>


```csharp
public CIMChartTrajectoryProfileLayer Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is enabled or not.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMChartTrajectoryProfileLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartTrajectoryProfileLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Gets or sets the object ID of the track feature.</p>


```csharp
public long ID { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Gets or sets the layer label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Gets or sets the layer symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartTrajectoryProfileLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


