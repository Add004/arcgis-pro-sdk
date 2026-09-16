# CIMKnowledgeGraphTableDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Represents a Knowledge Graph data connection.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphTableDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphTableDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Represents a Knowledge Graph data connection.</p>


```csharp
public CIMKnowledgeGraphTableDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphTableDataConnection.</p>


```csharp
public CIMKnowledgeGraphTableDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the OpenCypher definition query.</p>


```csharp
public string DefinitionQuery { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphTableDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphTableDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### InclusionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the InclusionSet for the table.</p>


```csharp
public string InclusionSetURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphTableDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphTableDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


