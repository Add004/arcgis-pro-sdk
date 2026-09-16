# CIMBAVariableBasedCriterion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis demographic variable-based criterion.</p>


## Object Signature

```csharp
public class CIMBAVariableBasedCriterion : CIMBASuitabilityAnalysisCriterion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAVariableBasedCriterion()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis demographic variable-based criterion.</p>


```csharp
public CIMBAVariableBasedCriterion()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAVariableBasedCriterion.</p>


```csharp
public CIMBAVariableBasedCriterion Clone()
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the data source used in calculation of distances.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can be value of baDataSource GP GPEnvironment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Reconstructs the CIMBAVariableBasedCriterion with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAVariableBasedCriterion FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAVariableBasedCriterion and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the  demographic variable name.</p>


```csharp
public string Variable { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableBasedCriterion.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


