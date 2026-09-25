# CIMKnowledgeGraphDataLoadingMissingDataOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Represents the options for handling missing data in a Knowledge Graph Data Loading Configuration.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphDataLoadingMissingDataOptions : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphDataLoadingMissingDataOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Represents the options for handling missing data in a Knowledge Graph Data Loading Configuration.</p>


```csharp
public CIMKnowledgeGraphDataLoadingMissingDataOptions()
```
### AllowCreationWhenAllDataMissing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to create entities or relationships with all missing data.</p>


```csharp
public bool AllowCreationWhenAllDataMissing { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphDataLoadingMissingDataOptions.</p>


```csharp
public CIMKnowledgeGraphDataLoadingMissingDataOptions Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphDataLoadingMissingDataOptions with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphDataLoadingMissingDataOptions FromJson(string json, JsonDeserializationSettings settings = null)
```
### MergePropertiesWithMissingData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating how to handle merge properties with missing data.</p>


```csharp
public KGMergePropertiesWithMissingData MergePropertiesWithMissingData { get; set; }
```
### OverwriteWithMissingValuesWhenMerging

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to overwrite existing values with missing values when merging.</p>


```csharp
public bool OverwriteWithMissingValuesWhenMerging { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphDataLoadingMissingDataOptions and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphDataLoadingMissingDataOptions.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


