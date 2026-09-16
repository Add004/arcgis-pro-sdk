# CIMLinkChartPropertyFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Represents additional settings used by a Link chart property filter.</p>


## Object Signature

```csharp
public class CIMLinkChartPropertyFilter : CIMLinkChartFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartPropertyFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Represents additional settings used by a Link chart property filter.</p>


```csharp
public CIMLinkChartPropertyFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartPropertyFilter.</p>


```csharp
public CIMLinkChartPropertyFilter Clone()
```
### DataType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Gets or sets the property data type that will be filtered.</p>


```csharp
public LinkChartFilterPropertyDataType DataType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartPropertyFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartPropertyFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartPropertyFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartPropertyFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


