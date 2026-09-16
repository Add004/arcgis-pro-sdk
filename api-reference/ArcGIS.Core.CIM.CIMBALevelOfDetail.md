# CIMBALevelOfDetail

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer level of detail.</p>


## Object Signature

```csharp
public class CIMBALevelOfDetail : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBALevelOfDetail()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer level of detail.</p>


```csharp
public CIMBALevelOfDetail()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBALevelOfDetail.</p>


```csharp
public CIMBALevelOfDetail Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Gets or sets the level of detail data connection.</p>


```csharp
[Obsolete("DataConnection is deprecated at 3.5. Use LevelOfDetailDataConnection instead.")]
public CIMStandardDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Reconstructs the CIMBALevelOfDetail with a specified state from a JSON encoding.</p>


```csharp
public static CIMBALevelOfDetail FromJson(string json, JsonDeserializationSettings settings = null)
```
### LevelID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Gets or sets the level of detail LevelID.</p>


```csharp
public string LevelID { get; set; }
```
### LevelOfDetailDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Gets or sets the level of detail data connection.</p>


```csharp
public CIMDataConnection LevelOfDetailDataConnection { get; set; }
```
### LevelOfDetailStatus

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Gets or sets the level of detail status.</p>


```csharp
public BAColorCodedLayerLODStatus LevelOfDetailStatus { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBALevelOfDetail and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBALevelOfDetail.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


