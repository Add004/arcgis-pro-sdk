# CIMTableView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Represents a table view in the project.</p>


## Object Signature

```csharp
public abstract class CIMTableView : CIMView, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTableView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Represents a table view in the project.</p>


```csharp
protected CIMTableView()
```
### AutoPopulateContingentValueFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether other contingent value fields should be automatically populated after a value is changed when only one match is valid.</p>


```csharp
public bool AutoPopulateContingentValueFields { get; set; }
```
### ColumnHeaderRowHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating the height for the column header row in the table.</p>


```csharp
public TableRowHeightType ColumnHeaderRowHeight { get; set; }
```
### DisplaySubtypeDomainDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display subtype and domain descriptions.</p>


```csharp
public bool DisplaySubtypeDomainDescriptions { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets the extent of the table view.</p>


```csharp
public Envelope Extent { get; set; }
```
### FieldOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets the field order as a string of field names.</p>


```csharp
public string FieldOrder { get; set; }
```
### FieldWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a property set of field width information.</p>


```csharp
public IDictionary<string, object> FieldWidth { get; set; }
```
### FrozenFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets the count of frozen fields.</p>


```csharp
public int FrozenFields { get; set; }
```
### HighlightInvalidContingentValueFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether invalid contingent value fields should be highlighted in the table.</p>


```csharp
public bool HighlightInvalidContingentValueFields { get; set; }
```
### HonorRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to honor ranges on the table view.</p>


```csharp
public bool HonorRange { get; set; }
```
### HonorTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to honor time on the table view.</p>


```csharp
public bool HonorTime { get; set; }
```
### QualifyJoinFieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to qualify field names when the table contains fields from a join.</p>


```csharp
public bool QualifyJoinFieldNames { get; set; }
```
### Ranges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets the ranges of the table view.</p>


```csharp
public CIMLayerRange[] Ranges { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating the height for the rows in the table.</p>


```csharp
public TableRowHeightType RowHeight { get; set; }
```
### SelectionMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to view the table in selection mode.</p>


```csharp
public bool SelectionMode { get; set; }
```
### ShowOnlyContingentValueFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the table field visibility settings should be overridden to only show fields that are part of one or more contingent value field groups.</p>


```csharp
public bool ShowOnlyContingentValueFields { get; set; }
```
### SortInformation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a property set containing sort information.</p>


```csharp
public IDictionary<string, object> SortInformation { get; set; }
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets the current time of the table view.</p>


```csharp
public TimeValue Time { get; set; }
```
### TimeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets a time relation which allows the start and end times to be included or excluded in the time query.</p>


```csharp
public esriTimeRelation TimeRelation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZoomLevel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableView.yml" sourcestartlinenumber="1">Gets or sets the zoom level of the table view.</p>


```csharp
public int ZoomLevel { get; set; }
```


