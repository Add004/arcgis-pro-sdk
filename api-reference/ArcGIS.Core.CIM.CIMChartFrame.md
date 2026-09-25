# CIMChartFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Layout element used to display a chart.</p>


## Object Signature

```csharp
public class CIMChartFrame : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartFrame()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Layout element used to display a chart.</p>


```csharp
public CIMChartFrame()
```
### ChartName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Gets or sets the chart to display.</p>


```csharp
public string ChartName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartFrame.</p>


```csharp
public CIMChartFrame Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Reconstructs the CIMChartFrame with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartFrame FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsDynamic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart is dynamic.</p>


```csharp
public bool IsDynamic { get; set; }
```
### MapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Gets or sets the layer or standalone table that defines the data to display.</p>


```csharp
public string MapMemberURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartFrame and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMapSeriesShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart uses the map series shape.</p>


```csharp
public bool UseMapSeriesShape { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFrame.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


