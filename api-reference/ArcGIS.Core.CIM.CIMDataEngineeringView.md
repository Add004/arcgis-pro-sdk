# CIMDataEngineeringView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Represents a data engineering statistics view.</p>


## Object Signature

```csharp
public class CIMDataEngineeringView : CIMView, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDataEngineeringView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Represents a data engineering statistics view.</p>


```csharp
public CIMDataEngineeringView()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDataEngineeringView.</p>


```csharp
public CIMDataEngineeringView Clone()
```
### Columns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the properties of statistics to display in the summary statistic view.</p>


```csharp
public CIMDataEngineeringStatisticColumn[] Columns { get; set; }
```
### DisplayDateTimeStatistics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show date statistics in the table.</p>


```csharp
public bool DisplayDateTimeStatistics { get; set; }
```
### DisplayNumericStatistics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show numeric statistics in the table.</p>


```csharp
public bool DisplayNumericStatistics { get; set; }
```
### DisplayTextStatistics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show text statistics in the table.</p>


```csharp
public bool DisplayTextStatistics { get; set; }
```
### FieldStatistics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets a collection of field statistics.</p>


```csharp
public CIMDataEngineeringFieldStatistics[] FieldStatistics { get; set; }
```
### FieldTypeFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the list of field type filters.</p>


```csharp
[Obsolete("FieldTypeFilter is deprecated at 3.1. ")]
public FieldType[] FieldTypeFilter { get; set; }
```
### FieldTypeFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the list of field type filters.</p>


```csharp
public esriFieldType[] FieldTypeFilters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Reconstructs the CIMDataEngineeringView with a specified state from a JSON encoding.</p>


```csharp
public static CIMDataEngineeringView FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayoutType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the view layout style.</p>


```csharp
public DataEngineeringViewLayoutType LayoutType { get; set; }
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the path of the Map for the item in the view.</p>


```csharp
public string MapURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the row height in pixels.</p>


```csharp
public int RowHeight { get; set; }
```
### SourceFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the source filter applied for calculating the statistics.</p>


```csharp
public DataEngineeringSourceFilterType SourceFilter { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDataEngineeringView and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseFieldAliases

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show field aliases in the view.</p>


```csharp
public bool UseFieldAliases { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZoomPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringView.yml" sourcestartlinenumber="1">Gets or sets the zoom level of the summary statistics table.</p>


```csharp
public int ZoomPercent { get; set; }
```


