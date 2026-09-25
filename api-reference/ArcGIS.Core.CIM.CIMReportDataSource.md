# CIMReportDataSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Represents the data source properties of a report. The data source can be a map member or external data.</p>


## Object Signature

```csharp
public class CIMReportDataSource : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportDataSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Represents the data source properties of a report. The data source can be a map member or external data.</p>


```csharp
public CIMReportDataSource()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportDataSource.</p>


```csharp
public CIMReportDataSource Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Gets or sets the data connection to the source.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DefinitionFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Gets or sets the definition query.
For map members, this can include a spatial filter.</p>


```csharp
public CIMDefinitionFilter DefinitionFilter { get; set; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Gets or sets the definition query.</p>


```csharp
public string DefinitionQuery { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Gets or sets the fields used by the report.</p>


```csharp
public CIMReportField[] Fields { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Reconstructs the CIMReportDataSource with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportDataSource FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Gets or sets the URI to a Layer or Standalone table in the project.</p>


```csharp
public string MapMemberURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportDataSource and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSelectionSet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the selection of the layer or table should be used for the report.</p>


```csharp
public bool UseSelectionSet { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDataSource.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


