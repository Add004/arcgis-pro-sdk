# CIMHuffModelDistanceParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Distance properties of the Huff Model calibration item.</p>


## Object Signature

```csharp
public class CIMHuffModelDistanceParameters : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHuffModelDistanceParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Distance properties of the Huff Model calibration item.</p>


```csharp
public CIMHuffModelDistanceParameters()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHuffModelDistanceParameters.</p>


```csharp
public CIMHuffModelDistanceParameters Clone()
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets data source used in calculation of distances.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can be value of baDataSource GP GPEnvironment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### DistanceUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets distance units used in calculation of distances.</p>


```csharp
public LinearUnit DistanceUnits { get; set; }
```
### Exponent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets the exponent.</p>


```csharp
public double Exponent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Reconstructs the CIMHuffModelDistanceParameters with a specified state from a JSON encoding.</p>


```csharp
public static CIMHuffModelDistanceParameters FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeOfDay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets time of day used in calculation of distances.</p>


```csharp
public TimeInstant TimeOfDay { get; set; }
```
### TimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets time units used in calculation of distances.</p>


```csharp
public esriTimeUnits TimeUnits { get; set; }
```
### TimeZone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets time zone used in calculation of distances.</p>


```csharp
public string TimeZone { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHuffModelDistanceParameters and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TowardsFacility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to calculate distances toward facilities.</p>


```csharp
public bool TowardsFacility { get; set; }
```
### TravelModeId

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets ID of travel mode used in calculation of distances.</p>


```csharp
public string TravelModeId { get; set; }
```
### UseNetworkDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use network dataset to calculate distances.</p>


```csharp
public bool UseNetworkDistance { get; set; }
```
### UseTimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use time units.</p>


```csharp
public bool UseTimeUnits { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHuffModelDistanceParameters.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


