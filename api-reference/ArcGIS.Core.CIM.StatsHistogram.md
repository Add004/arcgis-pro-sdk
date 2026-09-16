# StatsHistogram

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Represents a raster statistics and histogram class.</p>


## Object Signature

```csharp
public class StatsHistogram : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### StatsHistogram()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Represents a raster statistics and histogram class.</p>


```csharp
public StatsHistogram()
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Reconstructs the StatsHistogram with a specified state from a JSON encoding.</p>


```csharp
public static StatsHistogram FromJson(string json)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Creates a JSON encoding of the StatsHistogram and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### covariances

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the covariances.</p>


```csharp
public double[] covariances { get; set; }
```
### histogram

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the historam values.</p>


```csharp
public double[] histogram { get; set; }
```
### limitMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the maximum limit.</p>


```csharp
public double? limitMax { get; set; }
```
### limitMaxSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified maximum limit.</p>


```csharp
public bool limitMaxSpecified { get; set; }
```
### limitMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the minimum limit.</p>


```csharp
public double? limitMin { get; set; }
```
### limitMinSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified minimum limit.</p>


```csharp
public bool limitMinSpecified { get; set; }
```
### max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the maximum.</p>


```csharp
public double? max { get; set; }
```
### maxSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified maximum.</p>


```csharp
public bool maxSpecified { get; set; }
```
### mean

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the mean.</p>


```csharp
public double? mean { get; set; }
```
### meanSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified mean.</p>


```csharp
public bool meanSpecified { get; set; }
```
### min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the minimum.</p>


```csharp
public double? min { get; set; }
```
### minSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified minimum.</p>


```csharp
public bool minSpecified { get; set; }
```
### nBands

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the number of bands.</p>


```csharp
public long? nBands { get; set; }
```
### nBandsSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified number of bands.</p>


```csharp
public bool nBandsSpecified { get; set; }
```
### nsamples

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the number of samples.</p>


```csharp
public double? nsamples { get; set; }
```
### nsamplesSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified number of samples.</p>


```csharp
public bool nsamplesSpecified { get; set; }
```
### resolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the resolution.</p>


```csharp
public double? resolution { get; set; }
```
### resolutionSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified resolution.</p>


```csharp
public bool resolutionSpecified { get; set; }
```
### stddev

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the standard deviation.</p>


```csharp
public double? stddev { get; set; }
```
### stddevSpecified

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.StatsHistogram.yml" sourcestartlinenumber="1">Gets and sets the specified standard deviation.</p>


```csharp
public bool stddevSpecified { get; set; }
```


