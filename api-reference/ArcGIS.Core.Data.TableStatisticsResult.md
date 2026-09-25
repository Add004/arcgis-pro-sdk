# TableStatisticsResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsResult.yml" sourcestartlinenumber="1">Reports the results of statistics calculations.</p>


## Object Signature

```csharp
public sealed class TableStatisticsResult
```


## Members

### GroupBy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsResult.yml" sourcestartlinenumber="1">Gets the list of <code>GroupBy</code> results where each <code>KeyValuePair</code> element's <code>Key</code> is a <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>
used for the <code>GROUP BY</code> and the corresponding <code>Value</code> is the value of the <code>field</code>.</p>


```csharp
public IReadOnlyList<KeyValuePair<Field, object>> GroupBy { get; }
```
### StatisticsResults

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableStatisticsResult.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.StatisticsResult" data-throw-if-not-resolved="false"></xref>s that contain the results of statistics calculations.</p>


```csharp
public IReadOnlyList<StatisticsResult> StatisticsResults { get; }
```


