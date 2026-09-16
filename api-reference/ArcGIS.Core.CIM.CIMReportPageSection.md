# CIMReportPageSection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Represents a supplemental page section of a report.</p>


## Object Signature

```csharp
public class CIMReportPageSection : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportPageSection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Represents a supplemental page section of a report.</p>


```csharp
public CIMReportPageSection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportPageSection.</p>


```csharp
public CIMReportPageSection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Reconstructs the CIMReportPageSection with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportPageSection FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludePageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to include page number elements.</p>


```csharp
public bool IncludePageNumber { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportPageSection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageSection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


