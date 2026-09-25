# CIMStatisticalDataCollectionField

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Represents a field of a statistical data collection that matches to existing field in referenced feature dataset.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionField : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionField()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Represents a field of a statistical data collection that matches to existing field in referenced feature dataset.</p>


```csharp
public CIMStatisticalDataCollectionField()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the alias of the field.</p>


```csharp
public string Alias { get; set; }
```
### ApportionmentMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets how the values from the feature service are apportioned. For local data it should be one of the apportionment method from default hierarchy of the specified dataset. Use ?GEOM? for Area apportionment.</p>


```csharp
public string ApportionmentMethod { get; set; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the category of the field.</p>


```csharp
public string Category { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionField.</p>


```csharp
public CIMStatisticalDataCollectionField Clone()
```
### FieldFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets how to display values of the field in reports.</p>


```csharp
public StatisticalReportFieldFormat FieldFormat { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionField with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionField FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the field name from the data.</p>


```csharp
public string Name { get; set; }
```
### OutputFieldType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the type of the field for enrich output. For example, if we want to have a script variable returning String type values (like TLIFENAME variable in US dataset),
or when the input (SDCX layer) fields are Integers we want to have integer output too.</p>


```csharp
public esriFieldType OutputFieldType { get; set; }
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the number of digits in a number. For example, the number 56.78 has a precision of 4. Precision is only valid for fields that are numeric.</p>


```csharp
public int Precision { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Script

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the additional attribute for 'Script' summary type that defines script which should be calculated.</p>


```csharp
public string Script { get; set; }
```
### ScriptLanguage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the additional attribute for 'Script' summary type that defines script language used by 'Script' attribute.
Currently only Python is supported.</p>


```csharp
public LabelExpressionEngine ScriptLanguage { get; set; }
```
### ShowInDataBrowser

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the field will be shown in the Data Browser control in ArcGIS Pro.</p>


```csharp
public bool ShowInDataBrowser { get; set; }
```
### SummaryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the summary type how apportioned values are summarized to produce the final result.</p>


```csharp
public StatisticalDataCollectionSummaryType SummaryType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionField and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UsedFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the additional attribute for 'Script' summary type that defines another fields used by script.
These may include feature class fields (even non-existing in calculator?) and another scripts.</p>


```csharp
public string[] UsedFields { get; set; }
```
### Vintage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the description of vintage of the data (For example, &quot;US2018 Q4&quot;).</p>


```csharp
public string Vintage { get; set; }
```
### WeightFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Gets or sets the additional attribute for 'Average' summary type that defines which field should be used to get weighted sum.</p>


```csharp
public string WeightFieldName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionField.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


