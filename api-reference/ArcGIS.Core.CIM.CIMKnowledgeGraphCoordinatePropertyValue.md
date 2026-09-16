# CIMKnowledgeGraphCoordinatePropertyValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Represents a coordinate property value.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphCoordinatePropertyValue : CIMKnowledgeGraphPropertyValue, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphCoordinatePropertyValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Represents a coordinate property value.</p>


```csharp
public CIMKnowledgeGraphCoordinatePropertyValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphCoordinatePropertyValue.</p>


```csharp
public CIMKnowledgeGraphCoordinatePropertyValue Clone()
```
### FieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Gets or sets the field names of this property value.</p>


```csharp
public string[] FieldNames { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphCoordinatePropertyValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphCoordinatePropertyValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### InterpretAsLongitudeLatitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the coordinate should be
interpreted as long,lat (true) or lat,lon(false,default). This
value only has meaning when the coordinate is ambiguous. For example,
the coordinate &quot;34N 22E&quot; is not ambiguous as the latitude and longitude
are both defined by the coordinate. However, &quot;34 22&quot; is ambiguous since
it could mean either &quot;34N 22E&quot; or &quot;34E 22N&quot;. In this situation the value
of this property determines the recognized coordinate.</p>


```csharp
public bool InterpretAsLongitudeLatitude { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Gets or sets the spatial reference of the coordinates.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphCoordinatePropertyValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphCoordinatePropertyValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


