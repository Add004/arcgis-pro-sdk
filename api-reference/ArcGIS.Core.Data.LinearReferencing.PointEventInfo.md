# PointEventInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">Represents information for an event table with point events. Each row in the table references an event, and its location is expressed as
measurements along a route feature.</p>


## Object Signature

```csharp
public sealed class PointEventInfo : EventInfo
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">An event table contains information about assets, conditions, and events that can be located along route features.
There are two types of events: point events <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo" data-throw-if-not-resolved="false"></xref> and line events<xref href="ArcGIS.Core.Data.LinearReferencing.LineEventInfo" data-throw-if-not-resolved="false"></xref>.
A point event describes a discrete location along a route (a point), whereas a line event describes a portion of a route (a line).</p>


## Members

### PointEventInfo(Table, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PointEventInfo(Table pointEventTable, string routeIDFieldName, string measureFieldName)
```
### PointEventInfo(Table, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo" data-throw-if-not-resolved="false"></xref> class with an offset field.</p>


```csharp
public PointEventInfo(Table pointEventTable, string routeIDFieldName, string measureFieldName, string offsetFieldName)
```
### EventType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo.EventType" data-throw-if-not-resolved="false"></xref> of the event table.</p>


```csharp
public override EventType EventType { get; }
```
### MeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">Gets the name of the field containing the measure value associated with the point event.</p>


```csharp
public string MeasureFieldName { get; }
```


