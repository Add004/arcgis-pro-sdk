# CIMKGTypeIndex

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type Index.
It is primarily used to configure a property of an entity type or a relationship type within the data model visualization view.</p>


## Object Signature

```csharp
public class CIMKGTypeIndex : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGTypeIndex()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type Index.
It is primarily used to configure a property of an entity type or a relationship type within the data model visualization view.</p>


```csharp
public CIMKGTypeIndex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGTypeIndex.</p>


```csharp
public CIMKGTypeIndex Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Reconstructs the CIMKGTypeIndex with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGTypeIndex FromJson(string json, JsonDeserializationSettings settings = null)
```
### IndexName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Gets or sets the name of the index.</p>


```csharp
public string IndexName { get; set; }
```
### IsAscending

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the index is stored in ascending order.</p>


```csharp
public bool IsAscending { get; set; }
```
### IsUnique

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the index is used to enforce uniqueness.</p>


```csharp
public bool IsUnique { get; set; }
```
### PropertyNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Gets or sets the property names associated with the index.</p>


```csharp
public string[] PropertyNames { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGTypeIndex and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGTypeIndex.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


