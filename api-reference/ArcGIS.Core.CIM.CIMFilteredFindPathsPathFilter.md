# CIMFilteredFindPathsPathFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Filtered Find Paths Path Filter.
A path filter can be used for a specific instance, in this case the ID has a value,
or for all instances of a type, in this case the ID is null.</p>


## Object Signature

```csharp
public class CIMFilteredFindPathsPathFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFilteredFindPathsPathFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Filtered Find Paths Path Filter.
A path filter can be used for a specific instance, in this case the ID has a value,
or for all instances of a type, in this case the ID is null.</p>


```csharp
public CIMFilteredFindPathsPathFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFilteredFindPathsPathFilter.</p>


```csharp
public CIMFilteredFindPathsPathFilter Clone()
```
### FilterType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Gets or sets the filter type of the path filter.</p>


```csharp
public KGPathFilterType FilterType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMFilteredFindPathsPathFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMFilteredFindPathsPathFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Gets or sets the id of the entity/relationship instance used for the path filter.
If this id is null, then the path filter is used on all instances of the specified entity/relationship type.</p>


```csharp
public object ID { get; set; }
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Gets or sets whether the path filter is used for entities or relationships.</p>


```csharp
public KGPathFilterItemType ItemType { get; set; }
```
### ItemTypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Gets or sets the type name of the entity/relationship (type or instance) used for the path filter.</p>


```csharp
public string ItemTypeName { get; set; }
```
### PropertyFilterPredicate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Gets or sets the property filter predicate (openCypher syntax) associated with the path filter.
The predicate is only taken into account when ID has no value.</p>


```csharp
public string PropertyFilterPredicate { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFilteredFindPathsPathFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsPathFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


