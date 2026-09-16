# CIMPopupInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Represents pop-up info.</p>


## Object Signature

```csharp
public class CIMPopupInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPopupInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Represents pop-up info.</p>


```csharp
public CIMPopupInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPopupInfo.</p>


```csharp
public CIMPopupInfo Clone()
```
### ExpressionInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Gets or sets Arcade expressions that are referenced as fields in one or more elements in MediaInfos.</p>


```csharp
public CIMExpressionInfo[] ExpressionInfos { get; set; }
```
### FieldDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Gets or sets the pop-up field descriptions.</p>


```csharp
public CIMPopupFieldDescription[] FieldDescriptions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMPopupInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMPopupInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLayout

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Gets or sets the grid layout for the media infos.</p>


```csharp
public CIMPopupLayout GridLayout { get; set; }
```
### MediaInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Gets or sets the media infos.</p>


```csharp
public CIMMediaInfo[] MediaInfos { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelatedRecordSortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Gets or sets the field name and the sort order by which the related records will be ordered.
The items are defined by the related field name (Format: RelationshipName\FieldName) as the Keys and the sort order (Enum: Asc, Desc) as the Values.</p>


```csharp
public CIMStringMap[] RelatedRecordSortOrder { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPopupInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


