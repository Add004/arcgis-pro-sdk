# CIMChartTimeBinningProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Provides access to members that control time binning properties.</p>


## Object Signature

```csharp
public class CIMChartTimeBinningProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartTimeBinningProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Provides access to members that control time binning properties.</p>


```csharp
public CIMChartTimeBinningProperties()
```
### CalculateAutomaticTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the time interval units and size are automatically calculated.</p>


```csharp
public bool CalculateAutomaticTimeInterval { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartTimeBinningProperties.</p>


```csharp
public CIMChartTimeBinningProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMChartTimeBinningProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartTimeBinningProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Gets or sets the reference time value. Valid when TimeAggregationType property is set to ReferenceTime.</p>


```csharp
public TimeInstant ReferenceTime { get; set; }
```
### TimeAggregationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Gets or sets the time aggregation type.</p>


```csharp
public ChartTimeAggregationType TimeAggregationType { get; set; }
```
### TimeIntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Gets or sets the time interval size.</p>


```csharp
public double TimeIntervalSize { get; set; }
```
### TimeIntervalUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Gets or sets the units used for the time interval size.</p>


```csharp
public esriTimeUnits TimeIntervalUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartTimeBinningProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrimIncompleteTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether incomplete time intervals at the ends of time interval ranges are trimmed in order to avoid bias.</p>


```csharp
public bool TrimIncompleteTimeInterval { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTimeBinningProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


