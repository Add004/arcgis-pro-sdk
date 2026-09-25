# TableSortDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.TableSortDescription.yml" sourcestartlinenumber="1">Specifies how a sort operation should be carried out on a table or feature class.</p>


## Object Signature

```csharp
public sealed class TableSortDescription
```


## Members

### TableSortDescription(IEnumerable&lt;SortDescription&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.TableSortDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TableSortDescription</code> class.</p>


```csharp
public TableSortDescription(IEnumerable<SortDescription> sortDescriptions)
```
### QueryFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableSortDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.QueryFilter" data-throw-if-not-resolved="false"></xref> that filters what values should be returned once the table sort operation is completed.</p>


```csharp
public QueryFilter QueryFilter { get; set; }
```
### SortDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableSortDescription.yml" sourcestartlinenumber="1">Gets an <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing one or more <xref href="ArcGIS.Core.Data.SortDescription" data-throw-if-not-resolved="false"></xref>s.</p>


```csharp
public IReadOnlyList<SortDescription> SortDescriptions { get; }
```


