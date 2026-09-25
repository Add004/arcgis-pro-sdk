# CIMDatabaseRelateInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Represents database relationship info that is used to represent layer or table level overrides.</p>


## Object Signature

```csharp
public class CIMDatabaseRelateInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDatabaseRelateInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Represents database relationship info that is used to represent layer or table level overrides.</p>


```csharp
public CIMDatabaseRelateInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDatabaseRelateInfo.</p>


```csharp
public CIMDatabaseRelateInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMDatabaseRelateInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMDatabaseRelateInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelatedMapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Gets or sets the related layer/table URI.
<remark>
This value is used to disambiguate cases where the same data connection is used by multiple layers or tables in a map.
</remark></p>


```csharp
public string RelatedMapMemberURI { get; set; }
```
### RelationshipClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Gets or sets the relationship class Name.</p>


```csharp
public string RelationshipClassName { get; set; }
```
### ServiceRelateID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Gets or sets a integer indicating the relate ID when published in a map service.</p>


```csharp
public int ServiceRelateID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDatabaseRelateInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatabaseRelateInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


