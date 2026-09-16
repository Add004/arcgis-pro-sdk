# CIMKnowledgeGraphSpatialMergeWithinDistance

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Represents merging geometries within a specified distance.
The properties define a buffer which is used to perform an intersection.
The buffers are always created in the coordinate system of the import data.
If the import data has a geographic coordinate system, and the DistanceUnit is
a Linear Unit, geodesic buffers will be created.  Otherwise, planar buffers will be created.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphSpatialMergeWithinDistance : CIMKnowledgeGraphSpatialMerge, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphSpatialMergeWithinDistance()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Represents merging geometries within a specified distance.
The properties define a buffer which is used to perform an intersection.
The buffers are always created in the coordinate system of the import data.
If the import data has a geographic coordinate system, and the DistanceUnit is
a Linear Unit, geodesic buffers will be created.  Otherwise, planar buffers will be created.</p>


```csharp
public CIMKnowledgeGraphSpatialMergeWithinDistance()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphSpatialMergeWithinDistance.</p>


```csharp
public CIMKnowledgeGraphSpatialMergeWithinDistance Clone()
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Gets or sets the distance value in terms of the DistanceUnit.</p>


```csharp
public double Distance { get; set; }
```
### DistanceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Gets or sets the distance unit of the Distance property.</p>


```csharp
public Unit DistanceUnit { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphSpatialMergeWithinDistance with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphSpatialMergeWithinDistance FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphSpatialMergeWithinDistance and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphSpatialMergeWithinDistance.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


