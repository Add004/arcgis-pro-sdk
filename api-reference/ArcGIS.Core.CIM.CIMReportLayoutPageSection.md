# CIMReportLayoutPageSection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Represents a layout supplemental page section of a report.</p>


## Object Signature

```csharp
public class CIMReportLayoutPageSection : CIMReportPageSection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportLayoutPageSection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Represents a layout supplemental page section of a report.</p>


```csharp
public CIMReportLayoutPageSection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportLayoutPageSection.</p>


```csharp
public CIMReportLayoutPageSection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Reconstructs the CIMReportLayoutPageSection with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportLayoutPageSection FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayoutURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Gets or sets the layout URI.</p>


```csharp
public string LayoutURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportLayoutPageSection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportLayoutPageSection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


