# CIMGroupFooter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Represents a group footer section in a report.</p>


## Object Signature

```csharp
public class CIMGroupFooter : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGroupFooter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Represents a group footer section in a report.</p>


```csharp
public CIMGroupFooter()
```
### AlignSubsectionToBottom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to force the subsection to export at the bottom of the page.</p>


```csharp
public bool AlignSubsectionToBottom { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGroupFooter.</p>


```csharp
public CIMGroupFooter Clone()
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Gets or sets the grouping field for the section.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Reconstructs the CIMGroupFooter with a specified state from a JSON encoding.</p>


```csharp
public static CIMGroupFooter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGroupFooter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupFooter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


