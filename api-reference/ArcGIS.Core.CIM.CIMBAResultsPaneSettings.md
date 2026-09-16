# CIMBAResultsPaneSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Business Analyst Results Pane settings.</p>


## Object Signature

```csharp
public class CIMBAResultsPaneSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAResultsPaneSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Business Analyst Results Pane settings.</p>


```csharp
public CIMBAResultsPaneSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAResultsPaneSettings.</p>


```csharp
public CIMBAResultsPaneSettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMBAResultsPaneSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAResultsPaneSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### HistogramBinCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the number of bins in the histogram chart.</p>


```csharp
public int HistogramBinCount { get; set; }
```
### HistogramFillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the fill symbol properties of the histogram chart bar.</p>


```csharp
public CIMChartFillSymbolProperties HistogramFillSymbolProperties { get; set; }
```
### HistogramSubsetSelectionMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the histogram chart subset selection method.</p>


```csharp
public BAHistogramSubsetSelectionMethod HistogramSubsetSelectionMethod { get; set; }
```
### HistogramSubsetSelectionValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the histogram chart subset selection method value.</p>


```csharp
public double HistogramSubsetSelectionValue { get; set; }
```
### MatchTopBottomChartToLayerSymbology

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether top/bottom charts should match layer symbology.</p>


```csharp
public bool MatchTopBottomChartToLayerSymbology { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TableSortDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the direction of the sort in the Results Pane table.</p>


```csharp
public SortOrderType TableSortDirection { get; set; }
```
### TableSortField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the sort field of the Results Pane table.</p>


```csharp
public string TableSortField { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAResultsPaneSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAResultsPaneSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


