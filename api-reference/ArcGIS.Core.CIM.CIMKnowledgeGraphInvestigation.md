# CIMKnowledgeGraphInvestigation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Investigation.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphInvestigation : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphInvestigation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Investigation.</p>


```csharp
public CIMKnowledgeGraphInvestigation()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphInvestigation.</p>


```csharp
public CIMKnowledgeGraphInvestigation Clone()
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the custom properties of the investigation. Custom properties are limited to key / value pairs of strings and developers are fully responsible for stored content.</p>


```csharp
public CIMStringMap[] CustomProperties { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DataLoadingConfigurations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of Data Loading Configurations referenced by this Investigation.
All configurations are expected to have unique names.</p>


```csharp
public CIMKnowledgeGraphDataLoadingConfiguration[] DataLoadingConfigurations { get; set; }
```
### DataModelVisualizations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of Data Model Visualizations referenced by this Investigation.
All Data Model Visualizations are expected to have unique names.</p>


```csharp
public CIMKGDataModelVisualization[] DataModelVisualizations { get; set; }
```
### FilteredFindPathsConfigurations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of Filtered Find Paths Configurations referenced by this Investigation.
All configurations are expected to have unique names.</p>


```csharp
public CIMFilteredFindPathsConfiguration[] FilteredFindPathsConfigurations { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphInvestigation with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphInvestigation FromJson(string json, JsonDeserializationSettings settings = null)
```
### LoadDataPlans

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of Load Data Plans referenced by this Investigation.
All plans are expected to have unique names.</p>


```csharp
public CIMKnowledgeGraphLoadDataPlan[] LoadDataPlans { get; set; }
```
### QueryDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of query definitions referenced by this Investigation.
All query definitions are expected to have unique names.</p>


```csharp
public CIMKnowledgeGraphQueryDefinition[] QueryDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SearchDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of search definitions referenced by this Investigation.
All search definitions are expected to have unique names.</p>


```csharp
public CIMKnowledgeGraphSearchDefinition[] SearchDefinitions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphInvestigation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TypeInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Gets or sets the array of Knowledge Graph Investigation Type Infos referenced by this Investigation.
All infos are expected to have unique type names.</p>


```csharp
public CIMKnowledgeGraphInvestigationTypeInfo[] TypeInfos { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphInvestigation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


