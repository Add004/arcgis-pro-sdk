# CIMChartDimensionalProfileCCDCArguments

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Represents arguments to be used to plot change detection over time.</p>


## Object Signature

```csharp
public class CIMChartDimensionalProfileCCDCArguments : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartDimensionalProfileCCDCArguments()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Represents arguments to be used to plot change detection over time.</p>


```csharp
public CIMChartDimensionalProfileCCDCArguments()
```
### ChiSquaredThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Gets or sets the chi squared statistic change probability threshold.</p>


```csharp
public double ChiSquaredThreshold { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartDimensionalProfileCCDCArguments.</p>


```csharp
public CIMChartDimensionalProfileCCDCArguments Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Reconstructs the CIMChartDimensionalProfileCCDCArguments with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartDimensionalProfileCCDCArguments FromJson(string json, JsonDeserializationSettings settings = null)
```
### MinimumAnomaly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Gets or sets the minimum number of consecutive anomaly observations that must occur before an event is considered a change.</p>


```csharp
public int MinimumAnomaly { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TemporalMaskBandIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Gets or sets the bandIDs for temporal masking.</p>


```csharp
public int[] TemporalMaskBandIDs { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartDimensionalProfileCCDCArguments and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpdatingFrequency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Gets or sets the frequency in years at which to update the time series model with new observations.</p>


```csharp
public double UpdatingFrequency { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileCCDCArguments.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


