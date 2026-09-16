# EventInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">Represents information for an event table. Each row in the table references an event, and its location is expressed as measurements along a route feature.</p>


## Object Signature

```csharp
public abstract class EventInfo
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">An event is a linear, continuous, or point feature that occurs along a route feature. Anything that occurs on or describes a route feature can
be an event. There are two types of events: point events <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventInfo" data-throw-if-not-resolved="false"></xref> and line events<xref href="ArcGIS.Core.Data.LinearReferencing.LineEventInfo" data-throw-if-not-resolved="false"></xref>.
A point event describes a discrete location along a route (a point), whereas a line event describes a portion of a route (a line).</p>


## Members

### EventType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.LinearReferencing.EventInfo.EventType" data-throw-if-not-resolved="false"></xref> of this class.</p>


```csharp
public abstract EventType EventType { get; }
```
### GetEventTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">Gets the event table used to create the <xref href="ArcGIS.Core.Data.LinearReferencing.EventInfo" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public Table GetEventTable()
```
### OffsetFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">Gets the name of the field that identifies the offset of the point or line from the underlying route as defined by the measure field.</p>


```csharp
public string OffsetFieldName { get; }
```
### RouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">Gets the name of the route identifier field that uniquely identifies each route in a route feature class.</p>


```csharp
public string RouteIDFieldName { get; }
```


