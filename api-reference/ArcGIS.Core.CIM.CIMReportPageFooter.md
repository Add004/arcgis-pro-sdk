# CIMReportPageFooter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Represents a page footer in a report.</p>


## Object Signature

```csharp
public class CIMReportPageFooter : CIMReportSectionElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportPageFooter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Represents a page footer in a report.</p>


```csharp
public CIMReportPageFooter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportPageFooter.</p>


```csharp
public CIMReportPageFooter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Reconstructs the CIMReportPageFooter with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportPageFooter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportPageFooter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportPageFooter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


