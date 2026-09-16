# CIMTimelineLaneMapMemberDataSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Represents a map member source of temporal data.</p>


## Object Signature

```csharp
public class CIMTimelineLaneMapMemberDataSource : CIMTimelineLaneDataSource, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimelineLaneMapMemberDataSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Represents a map member source of temporal data.</p>


```csharp
public CIMTimelineLaneMapMemberDataSource()
```
### CategoryField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Gets or sets the value of the category field name.</p>


```csharp
public string CategoryField { get; set; }
```
### CategoryValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Gets or sets the value of the category field value.</p>


```csharp
public object CategoryValue { get; set; }
```
### CategoryValueType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Gets or sets the value of the category field value type.</p>


```csharp
public esriFieldType CategoryValueType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimelineLaneMapMemberDataSource.</p>


```csharp
public CIMTimelineLaneMapMemberDataSource Clone()
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Gets or sets the value of the display field name.</p>


```csharp
public string DisplayField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Reconstructs the CIMTimelineLaneMapMemberDataSource with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimelineLaneMapMemberDataSource FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Gets or sets the value of the map member uri.</p>


```csharp
public string MapMemberURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimelineLaneMapMemberDataSource and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneMapMemberDataSource.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


