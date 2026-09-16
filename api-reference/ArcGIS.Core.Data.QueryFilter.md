# QueryFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a query against a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class QueryFilter
```


## Members

### QueryFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a query against a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public QueryFilter()
```
### FullTextExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the full text expression used for filtering data in the underlying data store.</p>


```csharp
public FullTextExpression FullTextExpression { get; set; }
```
### ObjectIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the list of objectIDs used for filtering data in the underlying data store.</p>


```csharp
public IReadOnlyList<long> ObjectIDs { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the positional offset returned by the query.</p>


```csharp
public int Offset { get; set; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the spatial reference in which the features will be returned.</p>


```csharp
public SpatialReference OutputSpatialReference { get; set; }
```
### PostfixClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the postfix clause used by the filter.</p>


```csharp
public string PostfixClause { get; set; }
```
### PrefixClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the prefix clause used by the filter.</p>


```csharp
public string PrefixClause { get; set; }
```
### RowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the limit to the number of rows returned by the query.</p>


```csharp
public int RowCount { get; set; }
```
### SubFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets a comma (,) delimited string containing the names of fields for which values should be returned by the query.</p>


```csharp
public string SubFields { get; set; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.QueryFilter.yml" sourcestartlinenumber="1">Gets or sets the where clause used to filter the rows returned.</p>


```csharp
public string WhereClause { get; set; }
```


