# QueryDef

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Provides a capability to create virtual tables that represent queries involving one or more tables from the <b>same</b> geodatabase.</p>


## Object Signature

```csharp
public class QueryDef
```


## Members

### QueryDef()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Core.Data.QueryDef" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public QueryDef()
```
### PostfixClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Gets or sets the postfix clause used by the filter.</p>


```csharp
public string PostfixClause { get; set; }
```
### PrefixClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Gets or sets the prefix clause used by the query.</p>


```csharp
public string PrefixClause { get; set; }
```
### SubFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Gets or sets a comma (,) delimited string containing the names of fields for which values should be returned by the query.</p>


```csharp
public string SubFields { get; set; }
```
### Tables

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Gets or sets a comma (,) delimited string of tables for use in the query.</p>


```csharp
public string Tables { get; set; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryDef.yml" sourcestartlinenumber="1">Gets or sets the where clause used to filter the rows returned.</p>


```csharp
public string WhereClause { get; set; }
```


