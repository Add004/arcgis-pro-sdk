# CIMBAPointLayerBasedCriterion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis point layer-based criterion.</p>


## Object Signature

```csharp
public class CIMBAPointLayerBasedCriterion : CIMBASuitabilityAnalysisCriterion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAPointLayerBasedCriterion()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis point layer-based criterion.</p>


```csharp
public CIMBAPointLayerBasedCriterion()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAPointLayerBasedCriterion.</p>


```csharp
public CIMBAPointLayerBasedCriterion Clone()
```
### CutoffDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the Cutoff Distance. 0 for no cutoff.</p>


```csharp
public double CutoffDistance { get; set; }
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the data source used in calculation of distances.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can be value of baDataSource GP GPEnvironment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### DistanceUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets distance units used in calculation of distances.</p>


```csharp
public LinearUnit DistanceUnits { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Reconstructs the CIMBAPointLayerBasedCriterion with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAPointLayerBasedCriterion FromJson(string json, JsonDeserializationSettings settings = null)
```
### PointCriterionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the point criterion Type.</p>


```csharp
public BAPointCriterionType PointCriterionType { get; set; }
```
### PointLayerDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the data connection to the Point Layer.</p>


```csharp
public CIMStandardDataConnection PointLayerDataConnection { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SiteCentersLayerDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the data connection to the Site Centers Layer.</p>


```csharp
public CIMStandardDataConnection SiteCentersLayerDataConnection { get; set; }
```
### SiteCentersLayerId

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the Site Centers Layer Id.</p>


```csharp
public string SiteCentersLayerId { get; set; }
```
### SiteLayerIdField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the Site Layer Id Field name.</p>


```csharp
public string SiteLayerIdField { get; set; }
```
### StatisticsType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the Statistics Type.</p>


```csharp
public BAPointStatisticsType StatisticsType { get; set; }
```
### TimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets time units used in calculation of distances.</p>


```csharp
public esriTimeUnits TimeUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAPointLayerBasedCriterion and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TravelModeId

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets ID of travel mode used in calculation of distances.</p>


```csharp
public string TravelModeId { get; set; }
```
### UseNetworkDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use network dataset to calculate distances.</p>


```csharp
public bool UseNetworkDistance { get; set; }
```
### UseTimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use time units.</p>


```csharp
public bool UseTimeUnits { get; set; }
```
### WeightField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the Weight Field.</p>


```csharp
public string WeightField { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAPointLayerBasedCriterion.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


