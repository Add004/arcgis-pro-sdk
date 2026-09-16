# QueryTableDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.QueryTableDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <code>query table</code>, which is a virtual table that represents queries involving one or more tables from the <b>same</b> geodatabase.</p>


## Object Signature

```csharp
public sealed class QueryTableDescription
```


## Members

### QueryTableDescription(QueryDef)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.QueryTableDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>QueryTableDescription</code> class.</p>


```csharp
public QueryTableDescription(QueryDef queryDef)
```
### MakeCopy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryTableDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a copy of the data should be copied on the client side in order to create the <code>query table</code>.</p>


```csharp
public bool MakeCopy { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryTableDescription.yml" sourcestartlinenumber="1">Gets or sets the name of the <code>query table</code>.</p>


```csharp
public string Name { get; set; }
```
### PrimaryKeys

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryTableDescription.yml" sourcestartlinenumber="1">Gets or sets the comma-separated list of key fields to be used to manufacture ObjectIDs.</p>


```csharp
public string PrimaryKeys { get; set; }
```
### QueryDef

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryTableDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.QueryDef" data-throw-if-not-resolved="false"></xref> that was passed into the <code>QueryTableDescription</code> constructor.</p>


```csharp
public QueryDef QueryDef { get; }
```


