# CIMReportWatermark

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Represents a watermark in a report.</p>


## Object Signature

```csharp
public class CIMReportWatermark : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportWatermark()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Represents a watermark in a report.</p>


```csharp
public CIMReportWatermark()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportWatermark.</p>


```csharp
public CIMReportWatermark Clone()
```
### Element

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Gets or sets the element for the watermark.</p>


```csharp
public CIMElement Element { get; set; }
```
### ExcludePageNumbers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Gets or sets the comma delimited list of excluded page numbers.</p>


```csharp
public string ExcludePageNumbers { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Reconstructs the CIMReportWatermark with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportWatermark FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsBackground

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the overlay draws in the background of the report, else it draws on the foreground.</p>


```csharp
public bool IsBackground { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportWatermark and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportWatermark.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


