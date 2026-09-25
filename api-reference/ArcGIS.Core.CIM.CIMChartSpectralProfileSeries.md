# CIMChartSpectralProfileSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Represents a chart spectral profile series.</p>


## Object Signature

```csharp
public class CIMChartSpectralProfileSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartSpectralProfileSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Represents a chart spectral profile series.</p>


```csharp
public CIMChartSpectralProfileSeries()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartSpectralProfileSeries.</p>


```csharp
public CIMChartSpectralProfileSeries Clone()
```
### DisplayMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Gets or sets how this spectral profile is displayed.</p>


```csharp
public SpectralProfileDisplayMode DisplayMode { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartSpectralProfileSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartSpectralProfileSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the horizontal unit to be displayed in the chart.</p>


```csharp
public SpectralProfileHorizontalUnit HorizontalUnit { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowOutliers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the box plot outliers.</p>


```csharp
public bool ShowOutliers { get; set; }
```
### StandardizeValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to calculate standardized values for box plot.</p>


```csharp
public bool StandardizeValues { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartSpectralProfileSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSpectralProfileSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


