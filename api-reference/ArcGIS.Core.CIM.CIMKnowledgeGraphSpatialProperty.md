# CIMKnowledgeGraphSpatialProperty

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Represents a Spatial Knowledge Graph Data Loading Property used for entities. This
class is expected to be used only when the Type of property is esriFieldTypeGeometry.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphSpatialProperty : CIMKnowledgeGraphProperty, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphSpatialProperty()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Represents a Spatial Knowledge Graph Data Loading Property used for entities. This
class is expected to be used only when the Type of property is esriFieldTypeGeometry.</p>


```csharp
public CIMKnowledgeGraphSpatialProperty()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphSpatialProperty.</p>


```csharp
public CIMKnowledgeGraphSpatialProperty Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphSpatialProperty with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphSpatialProperty FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Gets or sets the geometry type of the property. Currently, only allowed values:</p>
<ul sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="2">
<li sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="2">esriGeometryPoint</li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="3">esriGeometryMultipoint</li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="4">esriGeometryPolyline</li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="5">esriGeometryPolygon
Others will be allowed in future.</li>
</ul>


```csharp
public esriGeometryType GeometryType { get; set; }
```
### KeepAllWhenMerging

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether all geometry values should be kept when merging.
Only applies when GeometryType is a multi-part geometry.</p>


```csharp
public bool KeepAllWhenMerging { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialMerge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Gets or sets a value describing how to handle spatial merge.
If not set, there is no spatial merge.</p>


```csharp
public CIMKnowledgeGraphSpatialMerge SpatialMerge { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Gets or sets the spatial reference of the property.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphSpatialProperty and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialProperty.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


