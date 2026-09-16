# StatisticsResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">Reports the results of statistics computation on a specific <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class StatisticsResult
```


## Members

### Average

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">The result of the <xref href="ArcGIS.Core.Data.StatisticsFunction.Average" data-throw-if-not-resolved="false"></xref> if this function was set as an input; <code>double.NaN</code> otherwise.</p>


```csharp
public double Average { get; }
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">The result of the <xref href="ArcGIS.Core.Data.StatisticsFunction.Count" data-throw-if-not-resolved="false"></xref> if this function was set as an input; <code>int.MinValue</code> otherwise.</p>


```csharp
public long Count { get; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> upon which one or more statistics functions were performed.</p>


```csharp
public Field Field { get; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">The result of the <xref href="ArcGIS.Core.Data.StatisticsFunction.Max" data-throw-if-not-resolved="false"></xref> if this function was set as an input; <code>double.NaN</code> otherwise.</p>


```csharp
public double Max { get; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">The result of the <xref href="ArcGIS.Core.Data.StatisticsFunction.Min" data-throw-if-not-resolved="false"></xref> if this function was set as an input; <code>double.NaN</code> otherwise.</p>


```csharp
public double Min { get; }
```
### StandardDeviation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">The result of the <xref href="ArcGIS.Core.Data.StatisticsFunction.StandardDeviation" data-throw-if-not-resolved="false"></xref> if this function was set as an input; <code>double.NaN</code> otherwise.</p>


```csharp
public double StandardDeviation { get; }
```
### Sum

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.StatisticsResult.yml" sourcestartlinenumber="1">The result of the <xref href="ArcGIS.Core.Data.StatisticsFunction.Sum" data-throw-if-not-resolved="false"></xref> if this function was set as an input; <code>double.NaN</code> otherwise.</p>


```csharp
public double Sum { get; }
```


