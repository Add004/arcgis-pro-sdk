# CIMRelationshipMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Represents relationship media info.</p>


## Object Signature

```csharp
public class CIMRelationshipMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRelationshipMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Represents relationship media info.</p>


```csharp
public CIMRelationshipMediaInfo()
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRelationshipMediaInfo.</p>


```csharp
public CIMRelationshipMediaInfo Clone()
```
### DisplayCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the maximum number of related records to display.</p>


```csharp
public int DisplayCount { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMRelationshipMediaInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMRelationshipMediaInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelatedRecordSortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the field names and the types of sort order by which the related records will be ordered.
The items are defined by the related field name as the Keys and the sort order (Enum: Asc, Desc) as the Values.</p>


```csharp
public CIMStringMap[] RelatedRecordSortOrder { get; set; }
```
### RelationshipName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the name of the relationship.</p>


```csharp
public string RelationshipName { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRelationshipMediaInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelationshipMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


