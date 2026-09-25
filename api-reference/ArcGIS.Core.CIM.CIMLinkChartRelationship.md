# CIMLinkChartRelationship

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Represents a link chart relationship.</p>


## Object Signature

```csharp
public class CIMLinkChartRelationship : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartRelationship()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Represents a link chart relationship.</p>


```csharp
public CIMLinkChartRelationship()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartRelationship.</p>


```csharp
public CIMLinkChartRelationship Clone()
```
### DrawingInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the link drawing information. This specifies the link color, width, and dash style.</p>


```csharp
public CIMLinkChartLinkDrawingInfo DrawingInfo { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this relationship is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartRelationship with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartRelationship FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the Id of for the relationship.</p>


```csharp
public string ID { get; set; }
```
### KeyType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the KeyType. This specifies where the key fields are located.</p>


```csharp
public LinkChartRelationshipKeyType KeyType { get; set; }
```
### LabelingInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the link labeling information.</p>


```csharp
public CIMLinkChartLinkLabelingInfo LabelingInfo { get; set; }
```
### MapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the path to the foreign table or layer used to create the relationship.</p>


```csharp
public string MapMemberURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the name of the relationship.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceEntityBackingField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the source entity backing field for the relationship.</p>


```csharp
public string SourceEntityBackingField { get; set; }
```
### SourceEntityId

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the source entity id for the relationship.</p>


```csharp
public string SourceEntityId { get; set; }
```
### SourceEntityKeyField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the source entity key field for the relationship.</p>


```csharp
public string SourceEntityKeyField { get; set; }
```
### TargetEntityBackingField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the target entity backing field for the relationship.</p>


```csharp
public string TargetEntityBackingField { get; set; }
```
### TargetEntityId

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the target entity id for the relationship.</p>


```csharp
public string TargetEntityId { get; set; }
```
### TargetEntityKeyField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Gets or sets the target entity key field for the relationship.</p>


```csharp
public string TargetEntityKeyField { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartRelationship and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartRelationship.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


