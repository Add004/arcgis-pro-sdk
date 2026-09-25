# CIMBASuitabilityAnalysisResultsPaneSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Suitability Analysis Results Pane settings.</p>


## Object Signature

```csharp
public class CIMBASuitabilityAnalysisResultsPaneSettings : CIMBAResultsPaneSettings, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBASuitabilityAnalysisResultsPaneSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Suitability Analysis Results Pane settings.</p>


```csharp
public CIMBASuitabilityAnalysisResultsPaneSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBASuitabilityAnalysisResultsPaneSettings.</p>


```csharp
public CIMBASuitabilityAnalysisResultsPaneSettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMBASuitabilityAnalysisResultsPaneSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMBASuitabilityAnalysisResultsPaneSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### HistogramCriterionID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the criterion ID for the histogram chart.</p>


```csharp
public string HistogramCriterionID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScatterplotChartType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the scatterplot chart type.</p>


```csharp
public BAScatterplotChartType ScatterplotChartType { get; set; }
```
### ScatterplotDotSizeCriterionID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the criterion ID for the dot size of the scatterplot chart.</p>


```csharp
public string ScatterplotDotSizeCriterionID { get; set; }
```
### ScatterplotXAxisCriterionID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the criterion ID for the X-Axis of the scatterplot chart.</p>


```csharp
public string ScatterplotXAxisCriterionID { get; set; }
```
### ScatterplotYAxisCriterionID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the criterion ID for the Y-Axis of the scatterplot chart.</p>


```csharp
public string ScatterplotYAxisCriterionID { get; set; }
```
### ShowRegressionLineOnScatterplot

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the regression line should be shown on the scatterplot chart.</p>


```csharp
public bool ShowRegressionLineOnScatterplot { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBASuitabilityAnalysisResultsPaneSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisResultsPaneSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


