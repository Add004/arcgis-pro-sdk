# CIMBAVariableList

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Represents Business Analyst variable list.</p>


## Object Signature

```csharp
public class CIMBAVariableList : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAVariableList()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Represents Business Analyst variable list.</p>


```csharp
public CIMBAVariableList()
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets the name of the author of the variable list.</p>


```csharp
public string Author { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAVariableList.</p>


```csharp
public CIMBAVariableList Clone()
```
### CreationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets creation date of the variable list.</p>


```csharp
public TimeInstant CreationDate { get; set; }
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets data source of the variable list.
Structure of the value is TYPE;COUNTRY_INFO;LOCAL_DATA_INFO
where
TYPE can be ONLINE, LOCAL, or CUSTOM.
COUNTRY_INFO is country_id{|hierarchy}. For example, US|census or US.
LOCAL_DATA_INFO is ID of local dataset. For example, USA_ESRI_2019.
For example, for local US 2019 dataset it will be: &quot;LOCAL;;USA_ESRI_2019&quot;.
If online US data source is used, it may be &quot;ONLINE;US|census;&quot;.
Can be value of baDataSource GP GPEnvironment variable.
<a href="https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm" sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="10">https://pro.arcgis.com/en/pro-app/tool-reference/environment-settings/ba-data-source.htm</a>.</p>


```csharp
public string DataSource { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Reconstructs the CIMBAVariableList with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAVariableList FromJson(string json, JsonDeserializationSettings settings = null)
```
### IconData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets base64 encoded icon.</p>


```csharp
public string IconData { get; set; }
```
### LastRevisionDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets last revision date of the variable list.</p>


```csharp
public TimeInstant LastRevisionDate { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets name of variable list.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets the tags for the variable list. Tags are keywords or short phrases that facilitate discovery of the variable list. Separate terms with commas.</p>


```csharp
public string Tags { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAVariableList and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Gets or sets variables.</p>


```csharp
public CIMBAVariableListVariable[] Variables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAVariableList.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


