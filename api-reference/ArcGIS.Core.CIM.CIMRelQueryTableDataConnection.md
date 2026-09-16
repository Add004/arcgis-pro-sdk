# CIMRelQueryTableDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Represents a RelQuery table data connection.</p>


## Object Signature

```csharp
public class CIMRelQueryTableDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRelQueryTableDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Represents a RelQuery table data connection.</p>


```csharp
public CIMRelQueryTableDataConnection()
```
### Cardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the join cardinality.</p>


```csharp
public esriRelCardinality Cardinality { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRelQueryTableDataConnection.</p>


```csharp
public CIMRelQueryTableDataConnection Clone()
```
### DestinationTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the destination table.</p>


```csharp
public CIMDataConnection DestinationTable { get; set; }
```
### ForeignKey

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the foreign key.</p>


```csharp
public string ForeignKey { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMRelQueryTableDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMRelQueryTableDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### JoinForward

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is a forward join.</p>


```csharp
public bool JoinForward { get; set; }
```
### JoinType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the join type.</p>


```csharp
public esriJoinType JoinType { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### OneToFirst

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the join will be one-to-first.</p>


```csharp
public bool OneToFirst { get; set; }
```
### PrimaryKey

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the primary key.</p>


```csharp
public string PrimaryKey { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Gets or sets the source table data connection.</p>


```csharp
public CIMDataConnection SourceTable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRelQueryTableDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelQueryTableDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


