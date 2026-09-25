# CIMFeatureTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Represents a feature table.</p>


## Object Signature

```csharp
public class CIMFeatureTable : CIMDisplayTable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFeatureTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Represents a feature table.</p>


```csharp
public CIMFeatureTable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFeatureTable.</p>


```csharp
public CIMFeatureTable Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DefinitionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Gets or sets the DefinitionSet for the table.</p>


```csharp
public string DefinitionSetURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Reconstructs the CIMFeatureTable with a specified state from a JSON encoding.</p>


```csharp
public static CIMFeatureTable FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsLicensedDataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the data source is licensed.</p>


```csharp
public bool IsLicensedDataSource { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SearchOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Gets or sets the search order option.</p>


```csharp
public esriSearchOrder SearchOrder { get; set; }
```
### StudyArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Gets or sets an area that can be used to subset the rows in the virtual table.</p>


```csharp
public Envelope StudyArea { get; set; }
```
### StudyAreaSpatialRel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Gets or sets the study area spatial relationship.</p>


```csharp
public esriSpatialRelEnum StudyAreaSpatialRel { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFeatureTable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


