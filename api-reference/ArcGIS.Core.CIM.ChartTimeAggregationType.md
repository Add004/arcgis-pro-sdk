# ChartTimeAggregationType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.ChartTimeAggregationType.yml" sourcestartlinenumber="1">Options for choosing how time intervals are built for the aggregation of a time based X-axis field.</p>


## Object Signature

```csharp
public enum ChartTimeAggregationType
```


## Members

### CalendarIntervals

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ChartTimeAggregationType.yml" sourcestartlinenumber="1">Time intervals follow calendar breaks.</p>


```csharp
CalendarIntervals = 3
```
### EqualIntervalsFromEndTime

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ChartTimeAggregationType.yml" sourcestartlinenumber="1">Time intervals start with the last (latest) data point.</p>


```csharp
EqualIntervalsFromEndTime = 2
```
### EqualIntervalsFromStartTime

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ChartTimeAggregationType.yml" sourcestartlinenumber="1">Time intervals start with the first (earliest) data point.</p>


```csharp
EqualIntervalsFromStartTime = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ChartTimeAggregationType.yml" sourcestartlinenumber="1">No time aggregation is performed.</p>


```csharp
None = 0
```
### ReferenceTime

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ChartTimeAggregationType.yml" sourcestartlinenumber="1">Time intervals snap to reference time.</p>


```csharp
ReferenceTime = 4
```


