# CIMLinkChartEntity

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Represents a link chart entity.</p>


## Object Signature

```csharp
public class CIMLinkChartEntity : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartEntity()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Represents a link chart entity.</p>


```csharp
public CIMLinkChartEntity()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartEntity.</p>


```csharp
public CIMLinkChartEntity Clone()
```
### DrawingInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the node drawing information.</p>


```csharp
public CIMLinkChartNodeDrawingInfo DrawingInfo { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this entity is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartEntity with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartEntity FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the Id of for the entity.</p>


```csharp
public string ID { get; set; }
```
### KeyFieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the fields used to uniquely identify nodes. If duplicate values exist you can CollapseDuplicates.</p>


```csharp
public string[] KeyFieldNames { get; set; }
```
### LabelFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the field used to label nodes.</p>


```csharp
public string LabelFieldName { get; set; }
```
### LabelingInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the node labeling information.</p>


```csharp
public CIMLinkChartNodeLabelingInfo LabelingInfo { get; set; }
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the CIMPath for the layer used to create the entity.</p>


```csharp
public string LayerURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets the name of the entity.</p>


```csharp
public string Name { get; set; }
```
### NonSpatial

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the entity is non spatial. Where it has coordinates on the map. This is used to prevent drawing links on the map to the wrong nodes.</p>


```csharp
public bool NonSpatial { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartEntity and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartEntity.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


