# CIMSqlQueryDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Represents a SQL query data connection.</p>


## Object Signature

```csharp
public class CIMSqlQueryDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSqlQueryDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Represents a SQL query data connection.</p>


```csharp
public CIMSqlQueryDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSqlQueryDataConnection.</p>


```csharp
public CIMSqlQueryDataConnection Clone()
```
### CustomWorkspaceFactoryCLSID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the classID of the custom workspace factory.</p>


```csharp
public string CustomWorkspaceFactoryCLSID { get; set; }
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset type.</p>


```csharp
public esriDatasetType DatasetType { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the extent.</p>


```csharp
public Envelope Extent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMSqlQueryDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMSqlQueryDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the geometry type.</p>


```csharp
public esriGeometryType GeometryType { get; set; }
```
### IsTableBased

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the query is &quot;table based&quot; (retrieves all the columns from the table and has no where clause or postfix clause).</p>


```csharp
public bool IsTableBased { get; set; }
```
### MappedOIDFieldLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the auto generated Esri OID field will be 32-bit or 64-bit.</p>


```csharp
public MappedOIDFieldType MappedOIDFieldLength { get; set; }
```
### MaterializedViewProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the properties relevant to materialized view-based query layers.</p>


```csharp
public CIMMaterializedViewProperties MaterializedViewProperties { get; set; }
```
### OIDFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the OID fields.</p>


```csharp
public string OIDFields { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialIndexDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the spatial index dimension.</p>


```csharp
public int SpatialIndexDimension { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### SpatialStorageType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the spatial storage type.</p>


```csharp
public int SpatialStorageType { get; set; }
```
### SqlQuery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the SQL query.</p>


```csharp
public string SqlQuery { get; set; }
```
### Srid

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the SRID of the spatial reference.</p>


```csharp
public string Srid { get; set; }
```
### SridType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the SRID type.</p>


```csharp
public int SridType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSqlQueryDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace connection string.</p>


```csharp
public string WorkspaceConnectionString { get; set; }
```
### WorkspaceFactory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Gets or sets the workspace factory.</p>


```csharp
public WorkspaceFactory WorkspaceFactory { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSqlQueryDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


