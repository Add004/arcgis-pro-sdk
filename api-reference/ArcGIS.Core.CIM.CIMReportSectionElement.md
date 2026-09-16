# CIMReportSectionElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Represents a section of elements in a report.</p>


## Object Signature

```csharp
public class CIMReportSectionElement : CIMGroupElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportSectionElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Represents a section of elements in a report.</p>


```csharp
public CIMReportSectionElement()
```
### AutoGrowTextElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the height of Text elements in sections will grow based on their content.</p>


```csharp
public bool AutoGrowTextElements { get; set; }
```
### AutoSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the section height will grow and shrink to fit the content of the section.</p>


```csharp
public bool AutoSize { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportSectionElement.</p>


```csharp
public CIMReportSectionElement Clone()
```
### ElementFieldProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets the field properties that will be applied to the elements.</p>


```csharp
public CIMReportElementFieldProperties[] ElementFieldProperties { get; set; }
```
### ExcludePageNumberPages

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets the comma delimited list of pages to exclude the page number from.</p>


```csharp
public string ExcludePageNumberPages { get; set; }
```
### ExcludeSectionPages

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets the comma delimited list of pages to exclude the section from.</p>


```csharp
public string ExcludeSectionPages { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Reconstructs the CIMReportSectionElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportSectionElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### HonorColumns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the section should be displayed in columns.</p>


```csharp
public bool HonorColumns { get; set; }
```
### KeepSubsectionTogether

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to prevent a page break for a subsection.
This property can be applied to the report footer, group header, and group footer subsections.</p>


```csharp
public bool KeepSubsectionTogether { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartOnNewPage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the section should start on a new page.</p>


```csharp
public bool StartOnNewPage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportSectionElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportSectionElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


