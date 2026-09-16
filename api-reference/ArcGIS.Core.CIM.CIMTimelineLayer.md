# CIMTimelineLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Represents a layer in a timeline.</p>


## Object Signature

```csharp
public class CIMTimelineLayer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimelineLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Represents a layer in a timeline.</p>


```csharp
public CIMTimelineLayer()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the timeline layer alias.</p>


```csharp
public string Alias { get; set; }
```
### CategoryField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the value of the category field name.</p>


```csharp
[Obsolete("CategoryField is deprecated at 3.6. This property is obsolete. Use the DataSources property instead.")]
public string CategoryField { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimelineLayer.</p>


```csharp
public CIMTimelineLayer Clone()
```
### DataSources

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets timeline layer data sources.</p>


```csharp
public CIMTimelineLaneDataSource[] DataSources { get; set; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the value of the display field name.</p>


```csharp
[Obsolete("DisplayField is deprecated at 3.6. This property is obsolete. Use the DataSources property instead.")]
public string DisplayField { get; set; }
```
### DrawingInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the timeline layer drawing information.</p>


```csharp
public CIMTimelineLaneDrawingInfo DrawingInfo { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTimelineLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimelineLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the Id of for the timeline layer.</p>


```csharp
public string ID { get; set; }
```
### LayerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the timeline layer view type.</p>


```csharp
public TimelineLayerType LayerType { get; set; }
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets the value of the layer uri.</p>


```csharp
[Obsolete("LayerURI is deprecated at 3.6. This property is obsolete. Use the DataSources property instead.")]
public string LayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimelineLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the timeline layer is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


