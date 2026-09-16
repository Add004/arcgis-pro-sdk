# CIMReportElementFieldProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Represents field properties that will be applied to an element in a report.</p>


## Object Signature

```csharp
public class CIMReportElementFieldProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportElementFieldProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Represents field properties that will be applied to an element in a report.</p>


```csharp
public CIMReportElementFieldProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportElementFieldProperties.</p>


```csharp
public CIMReportElementFieldProperties Clone()
```
### Element

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the target element.</p>


```csharp
public string Element { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the source field.</p>


```csharp
public string Field { get; set; }
```
### Format

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Gets or sets the format for the source field value.</p>


```csharp
public CIMNumberFormat Format { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMReportElementFieldProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportElementFieldProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Statistic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Gets or sets the statistic to apply to the source field.</p>


```csharp
public FieldStatisticsFlag Statistic { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportElementFieldProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportElementFieldProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


