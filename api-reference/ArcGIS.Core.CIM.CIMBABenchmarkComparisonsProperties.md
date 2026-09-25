# CIMBABenchmarkComparisonsProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Benchmark Comparisons properties.</p>


## Object Signature

```csharp
public class CIMBABenchmarkComparisonsProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBABenchmarkComparisonsProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Benchmark Comparisons properties.</p>


```csharp
public CIMBABenchmarkComparisonsProperties()
```
### AboveAndBelowType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the type of the Above and Below benchmark style.</p>


```csharp
public BABenchmarkAboveAndBelowType AboveAndBelowType { get; set; }
```
### AboveColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets above color.</p>


```csharp
public CIMRGBColor AboveColor { get; set; }
```
### AddAverageRow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to add average row to the results table.</p>


```csharp
public bool AddAverageRow { get; set; }
```
### AddDifferenceField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to add difference benchmark field.</p>


```csharp
public bool AddDifferenceField { get; set; }
```
### AddMedianRow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to add median row to the results table.</p>


```csharp
public bool AddMedianRow { get; set; }
```
### AddPercentDifferenceField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to add % difference benchmark field.</p>


```csharp
public bool AddPercentDifferenceField { get; set; }
```
### AddStandardDeviationRow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to add standard deviation row to the results table.</p>


```csharp
public bool AddStandardDeviationRow { get; set; }
```
### BelowColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets below color.</p>


```csharp
public CIMRGBColor BelowColor { get; set; }
```
### BenchmarkFeatureID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets benchmark feature ID.</p>


```csharp
public string BenchmarkFeatureID { get; set; }
```
### BenchmarkMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a benchmark method.</p>


```csharp
public BABenchmarkMethod BenchmarkMethod { get; set; }
```
### BenchmarkStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets benchmark style.</p>


```csharp
public BABenchmarkStyle BenchmarkStyle { get; set; }
```
### BottomColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets bottom color.</p>


```csharp
public CIMColor BottomColor { get; set; }
```
### BottomRecordsNumber

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a bottom value for the Top and Bottom benchmark style.</p>


```csharp
public int BottomRecordsNumber { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBABenchmarkComparisonsProperties.</p>


```csharp
public CIMBABenchmarkComparisonsProperties Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a color ramp for High to Low, Above and Below and Quantiles benchmark styles.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the data source used in calculation of variables and standard geographies.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can be value of baDataSource GP GPEnvironment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### FillColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a fill color for the None benchmark style.</p>


```csharp
public CIMRGBColor FillColor { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMBABenchmarkComparisonsProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMBABenchmarkComparisonsProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeographyLevels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets standard geography levels that can be added to the results table.</p>


```csharp
public string[] GeographyLevels { get; set; }
```
### HigherExtremeLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a greater than value for Highlight Extremes benchmark style.</p>


```csharp
public double HigherExtremeLimit { get; set; }
```
### HighlightExtremesType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the type of the Highlight Extremes benchmark style.</p>


```csharp
public BABenchmarkHighlightExtremesType HighlightExtremesType { get; set; }
```
### InBetweenColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets in-between color.</p>


```csharp
public CIMRGBColor InBetweenColor { get; set; }
```
### IsTableTransposed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the results table is transposed.</p>


```csharp
public bool IsTableTransposed { get; set; }
```
### LowerExtremeLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a less than value for Highlight Extremes benchmark style.</p>


```csharp
public double LowerExtremeLimit { get; set; }
```
### MapVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a map variable.</p>


```csharp
public string MapVariable { get; set; }
```
### NameField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the Name field which is required.</p>


```csharp
public string NameField { get; set; }
```
### NeighboringGeographies

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets neighboring geographies that can be added to the results table.</p>


```csharp
public CIMBANeighboringGeographyInfo[] NeighboringGeographies { get; set; }
```
### NumberOfQuantiles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a number of quantiles for the Quantiles benchmark style.</p>


```csharp
public int NumberOfQuantiles { get; set; }
```
### OutlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets an outline color for a selected benchmark style.</p>


```csharp
public CIMRGBColor OutlineColor { get; set; }
```
### OutlineSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets an outline size for a selected benchmark style.</p>


```csharp
public double OutlineSize { get; set; }
```
### Quartile1Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets quartile 1 color.</p>


```csharp
public CIMRGBColor Quartile1Color { get; set; }
```
### Quartile2Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets quartile 2 color.</p>


```csharp
public CIMRGBColor Quartile2Color { get; set; }
```
### Quartile3Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets quartile 3 color.</p>


```csharp
public CIMRGBColor Quartile3Color { get; set; }
```
### Quartile4Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets quartile 4 color.</p>


```csharp
public CIMRGBColor Quartile4Color { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ResultsPaneSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the results pane settings.</p>


```csharp
public CIMBABenchmarkComparisonsResultsPaneSettings ResultsPaneSettings { get; set; }
```
### SiteAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the fields in the input features layer containing site-specific attributes.</p>


```csharp
public string[] SiteAttributes { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBABenchmarkComparisonsProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TopAndBottomType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the type of the Top and Bottom benchmark style.</p>


```csharp
public BABenchmarkTopAndBottomType TopAndBottomType { get; set; }
```
### TopColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets top color.</p>


```csharp
public CIMColor TopColor { get; set; }
```
### TopRecordsNumber

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets a top value for the Top and Bottom benchmark style.</p>


```csharp
public int TopRecordsNumber { get; set; }
```
### Variables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Gets or sets the variables from the data browser, such as income, population, or
spending, used to enrich the input features.</p>


```csharp
public string[] Variables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


