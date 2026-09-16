# LineEventInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Represents information for an event table with line events. Each row in the table references an event, and its location is expressed as
measurements along a route feature.</p>


## Object Signature

```csharp
public sealed class LineEventInfo : EventInfo
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">An event table contains information about assets, conditions, and events that can be located along route features.
There are two types of events: point events <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo" data-throw-if-not-resolved="false"></xref> and line events<xref href="ArcGIS.Core.Data.LinearReferencing.LineEventInfo" data-throw-if-not-resolved="false"></xref>.
A point event describes a discrete location along a route (a point), whereas a line event describes a portion of a route (a line).</p>


## Members

### LineEventInfo(Table, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.LineEventInfo" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public LineEventInfo(Table lineEventTable, string routeIDFieldName, string fromMeasureFieldName, string toMeasureFieldName)
```
### LineEventInfo(Table, string, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo" data-throw-if-not-resolved="false"></xref> class with an offset field.</p>


```csharp
public LineEventInfo(Table lineEventTable, string routeIDFieldName, string fromMeasureFieldName, string toMeasureFieldName, string offsetFieldName)
```
### EventType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.LinearReferencing.LineEventInfo.EventType" data-throw-if-not-resolved="false"></xref> of the event table.</p>


```csharp
public override EventType EventType { get; }
```
### FromMeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Gets the name of the field that identifies where the event starts within the route.</p>


```csharp
public string FromMeasureFieldName { get; }
```
### ToMeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Gets the name of the field that identifies where the event ends within the route.</p>


```csharp
public string ToMeasureFieldName { get; }
```


