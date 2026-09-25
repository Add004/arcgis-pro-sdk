# CIMReport

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Represents a report in a project.</p>


## Object Signature

```csharp
public class CIMReport : CIMLayout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReport()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Represents a report in a project.</p>


```csharp
public CIMReport()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReport.</p>


```csharp
public CIMReport Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Reconstructs the CIMReport with a specified state from a JSON encoding.</p>


```csharp
public static CIMReport FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Gets or sets the Height of the report.</p>


```csharp
public double Height { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartPage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Gets or sets the starting page for the report.</p>


```csharp
public int StartPage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReport and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Watermarks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Gets or sets a collection of watermark for the report.</p>


```csharp
public CIMReportWatermark[] Watermarks { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReport.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


