# CIMTableQueryNameDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Represents a table query name data connection.</p>


## Object Signature

```csharp
public class CIMTableQueryNameDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTableQueryNameDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Represents a table query name data connection.</p>


```csharp
public CIMTableQueryNameDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTableQueryNameDataConnection.</p>


```csharp
public CIMTableQueryNameDataConnection Clone()
```
### CopyLocally

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to copy data locally.</p>


```csharp
public bool CopyLocally { get; set; }
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the extent.</p>


```csharp
public Envelope Extent { get; set; }
```
### FeatureType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the feature type.</p>


```csharp
public esriFeatureType FeatureType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMTableQueryNameDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMTableQueryNameDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### PrimaryKeyFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the primary key fields.</p>


```csharp
public string PrimaryKeyFields { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShapeFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the shape field name.</p>


```csharp
public string ShapeFieldName { get; set; }
```
### ShapeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the shape type.</p>


```csharp
public esriGeometryType ShapeType { get; set; }
```
### SubFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the subfields.</p>


```csharp
public string SubFields { get; set; }
```
### Tables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the tables.</p>


```csharp
public string Tables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTableQueryNameDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the where clause.</p>


```csharp
public string WhereClause { get; set; }
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableQueryNameDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


