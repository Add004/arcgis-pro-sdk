# CIMRelatedReportSection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Represents a Related Report section of a report.</p>


## Object Signature

```csharp
public class CIMRelatedReportSection : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRelatedReportSection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Represents a Related Report section of a report.</p>


```csharp
public CIMRelatedReportSection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRelatedReportSection.</p>


```csharp
public CIMRelatedReportSection Clone()
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Gets or sets the data source for a Related Report.</p>


```csharp
public CIMReportDataSource DataSource { get; set; }
```
### Expressions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Gets or sets the expressions used by the related report.</p>


```csharp
public CIMExpressionInfo[] Expressions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Reconstructs the CIMRelatedReportSection with a specified state from a JSON encoding.</p>


```csharp
public static CIMRelatedReportSection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelateName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Gets or sets the relate or relationship class name.</p>


```csharp
public string RelateName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRelatedReportSection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelatedReportSection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


