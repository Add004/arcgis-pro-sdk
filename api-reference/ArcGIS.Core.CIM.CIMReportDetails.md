# CIMReportDetails

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Represents a details section of a report.</p>


## Object Signature

```csharp
public class CIMReportDetails : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportDetails()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Represents a details section of a report.</p>


```csharp
public CIMReportDetails()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportDetails.</p>


```csharp
public CIMReportDetails Clone()
```
### ColumnDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Gets or sets a value the direction records will be rendered in a column.</p>


```csharp
public ColumnDirection ColumnDirection { get; set; }
```
### ColumnGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Gets or sets the gap between data columns. Units in inches.</p>


```csharp
public double ColumnGap { get; set; }
```
### Columns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Gets or sets the number of columns for the details section.</p>


```csharp
public int Columns { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Reconstructs the CIMReportDetails with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportDetails FromJson(string json, JsonDeserializationSettings settings = null)
```
### KeepRecordTogether

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to prevent a page break for a record in the Details subsection.</p>


```csharp
public bool KeepRecordTogether { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowBackgroundColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Gets or sets the collection of background colors for each of the repeating rows.</p>


```csharp
public CIMColor[] RowBackgroundColors { get; set; }
```
### RowBackgroundCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Gets or sets the number of consecutive rows for each background color.</p>


```csharp
public int RowBackgroundCount { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportDetails and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDetails.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


