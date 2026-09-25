# CIMBACalculatedVariableDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Represents a Business Analyst Calculated Variable.</p>


## Object Signature

```csharp
public class CIMBACalculatedVariableDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBACalculatedVariableDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Represents a Business Analyst Calculated Variable.</p>


```csharp
public CIMBACalculatedVariableDocument()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the alias of the variable.</p>


```csharp
public string Alias { get; set; }
```
### AverageBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the average base of the variable.</p>


```csharp
public string AverageBase { get; set; }
```
### CardViewMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the Card View mode.</p>


```csharp
public bool CardViewMode { get; set; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the category of the variable.</p>


```csharp
public string Category { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBACalculatedVariableDocument.</p>


```csharp
public CIMBACalculatedVariableDocument Clone()
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the data source used in calculation of distances.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can act as the value of the baDataSource GP environment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### FieldFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets how to display the values of the custom variable in reports.</p>


```csharp
public StatisticalReportFieldFormat FieldFormat { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMBACalculatedVariableDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMBACalculatedVariableDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### HasIndexBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the variable has an index base.</p>


```csharp
public bool HasIndexBase { get; set; }
```
### IndexBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the index base of the variable.</p>


```csharp
public double IndexBase { get; set; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the length of the variable.</p>


```csharp
public int Length { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the name of the variable.</p>


```csharp
public string Name { get; set; }
```
### OutputType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the output type of the variable.</p>


```csharp
public esriFieldType OutputType { get; set; }
```
### PercentBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the percent base of the variable.</p>


```csharp
public string PercentBase { get; set; }
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the precision of the variable.</p>


```csharp
public int Precision { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Script

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the Python script (expression) which should be calculated.</p>


```csharp
public string Script { get; set; }
```
### SummaryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the summary type of the variable.</p>


```csharp
public BACalculatedVariableSummaryType SummaryType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBACalculatedVariableDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UsedVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the variables used in the script expression.
For example, if Script is &quot;!RENTER_CY! / !TOTPOP_CY!&quot;, UsedVariables contains &quot;RENTER_CY&quot; and &quot;TOTPOP_CY&quot;.</p>


```csharp
public string[] UsedVariables { get; set; }
```
### VariableDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Gets or sets the definition of the variable.</p>


```csharp
public string VariableDefinition { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBACalculatedVariableDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


