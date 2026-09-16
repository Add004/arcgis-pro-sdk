# CIMFilteredFindPathsEntity

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">When the ID property has a value, represents a single entity.
When the ID property is null, represents entities of a given entity type,
filtered by PropertyFilterPredicate if it is not empty.</p>


## Object Signature

```csharp
public class CIMFilteredFindPathsEntity : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFilteredFindPathsEntity()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">When the ID property has a value, represents a single entity.
When the ID property is null, represents entities of a given entity type,
filtered by PropertyFilterPredicate if it is not empty.</p>


```csharp
public CIMFilteredFindPathsEntity()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFilteredFindPathsEntity.</p>


```csharp
public CIMFilteredFindPathsEntity Clone()
```
### EntityTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Gets or sets the type name of the entity (type or instance) used as an origin/destination entity.</p>


```csharp
public string EntityTypeName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Reconstructs the CIMFilteredFindPathsEntity with a specified state from a JSON encoding.</p>


```csharp
public static CIMFilteredFindPathsEntity FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Gets or sets the id of the entity instance used as a origin/destination entity.
If this id is null, then the filtered find paths algorithm uses all instances of the specified entity type.</p>


```csharp
public object ID { get; set; }
```
### PropertyFilterPredicate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Gets or sets the property filter predicate (openCypher syntax) associated with the path filter.
The predicate is only taken into account when ID has no value.</p>


```csharp
public string PropertyFilterPredicate { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFilteredFindPathsEntity and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsEntity.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


