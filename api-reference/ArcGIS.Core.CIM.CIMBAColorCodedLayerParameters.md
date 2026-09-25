# CIMBAColorCodedLayerParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer Properties.</p>


## Object Signature

```csharp
public class CIMBAColorCodedLayerParameters : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAColorCodedLayerParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer Properties.</p>


```csharp
public CIMBAColorCodedLayerParameters()
```
### ActiveLevelOfDetail

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the level of details. It's a layer ID of a standard geography.
If ActiveLevelOfDetail is empty, automatic level selection based on the current map scale will be used.</p>


```csharp
public string ActiveLevelOfDetail { get; set; }
```
### ActiveLevelsGroup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the group of levels.</p>


```csharp
public string ActiveLevelsGroup { get; set; }
```
### AreaOfInterest

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the area of interest parameters.</p>


```csharp
public CIMBAAreaOfInterest AreaOfInterest { get; set; }
```
### BoundaryMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the Color Coded Layer boundary mode.</p>


```csharp
public BABoundaryMode BoundaryMode { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAColorCodedLayerParameters.</p>


```csharp
public CIMBAColorCodedLayerParameters Clone()
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the data source used in calculation of distances.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can be value of baDataSource GP GPEnvironment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Reconstructs the CIMBAColorCodedLayerParameters with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAColorCodedLayerParameters FromJson(string json, JsonDeserializationSettings settings = null)
```
### LevelsOfDetail

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the level of detail items.</p>


```csharp
public CIMBALevelOfDetail[] LevelsOfDetail { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RendererProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the Color Coded Map renderer properties.</p>


```csharp
public CIMBARendererProperties RendererProperties { get; set; }
```
### ResultsPaneSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the results pane settings.</p>


```csharp
public CIMBAResultsPaneSettings ResultsPaneSettings { get; set; }
```
### SecondaryVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the secondary demographic variable name.</p>


```csharp
public string SecondaryVariable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAColorCodedLayerParameters and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Gets or sets the  demographic variable name.</p>


```csharp
public string Variable { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerParameters.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


