# CIMGroupHeader

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Represents a group header section in a report.</p>


## Object Signature

```csharp
public class CIMGroupHeader : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGroupHeader()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Represents a group header section in a report.</p>


```csharp
public CIMGroupHeader()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGroupHeader.</p>


```csharp
public CIMGroupHeader Clone()
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Gets or sets the grouping field for the section.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Reconstructs the CIMGroupHeader with a specified state from a JSON encoding.</p>


```csharp
public static CIMGroupHeader FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RepeatOnEveryPage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the section should be displayed on every page.</p>


```csharp
public bool RepeatOnEveryPage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGroupHeader and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupHeader.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


