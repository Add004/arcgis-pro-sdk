# TableStatisticsDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsDescription.yml" sourcestartlinenumber="1">Specifies how statistics computations should be carried out against one or more fields in a table or feature class.</p>


## Object Signature

```csharp
public sealed class TableStatisticsDescription
```


## Members

### TableStatisticsDescription(IEnumerable&lt;StatisticsDescription&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>TableStatisticsDescription</code> class.</p>


```csharp
public TableStatisticsDescription(IEnumerable<StatisticsDescription> statisticsDescriptions)
```
### GroupBy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsDescription.yml" sourcestartlinenumber="1">Gets or sets a list of <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>s to be used for <code>GroupBy</code> during statistics computation.</p>


```csharp
public IReadOnlyList<Field> GroupBy { get; set; }
```
### OrderBy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsDescription.yml" sourcestartlinenumber="1">Gets or sets a list of <xref href="ArcGIS.Core.Data.SortDescription" data-throw-if-not-resolved="false"></xref>s to be used to sort the <code>TableStatisticsResults</code> that are returned.</p>


```csharp
public IReadOnlyList<SortDescription> OrderBy { get; set; }
```
### QueryFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.QueryFilter" data-throw-if-not-resolved="false"></xref> that constrains what data is used for statistics computation.</p>


```csharp
public QueryFilter QueryFilter { get; set; }
```
### StatisticsDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsDescription.yml" sourcestartlinenumber="1">Gets an <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of one or more <xref href="ArcGIS.Core.Data.StatisticsDescription" data-throw-if-not-resolved="false"></xref>s specifying what
statistics function(s) should be performed on a specific field.</p>


```csharp
public IReadOnlyList<StatisticsDescription> StatisticsDescriptions { get; }
```


