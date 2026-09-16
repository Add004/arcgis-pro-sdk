# CIMReportHeader

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Represents a report header section in a report.</p>


## Object Signature

```csharp
public class CIMReportHeader : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportHeader()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Represents a report header section in a report.</p>


```csharp
public CIMReportHeader()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportHeader.</p>


```csharp
public CIMReportHeader Clone()
```
### CoverPage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the report header is a cover page.</p>


```csharp
public bool CoverPage { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Reconstructs the CIMReportHeader with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportHeader FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportHeader and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportHeader.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


