# LineEventTableConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.yml" sourcestartlinenumber="1">Describes a line event table to hold events' information as the results of <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo.LocateFeatures(ArcGIS.Core.Data.FeatureClass%2cSystem.Double%2cArcGIS.Core.Data.LinearReferencing.EventTableConfiguration)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class LineEventTableConfiguration : EventTableConfiguration
```


## Members

### LineEventTableConfiguration(string, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.yml" sourcestartlinenumber="1">Construct an object to describe a line event table to hold events' information, <xref href="ArcGIS.Core.Data.LinearReferencing.EventInfo" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LineEventTableConfiguration(string eventTableName, string routeIDFieldName, string fromMeasureFieldName, string toMeasureFieldName)
```
### EventType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.yml" sourcestartlinenumber="1">Gets the event type, <xref href="ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.EventType" data-throw-if-not-resolved="false"></xref></p>


```csharp
public override EventType EventType { get; }
```
### FromMeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.yml" sourcestartlinenumber="1">Gets the name of the field that identifies where the event starts within the route.</p>


```csharp
public string FromMeasureFieldName { get; }
```
### ToMeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.yml" sourcestartlinenumber="1">Gets the name of the field that identifies where the event ends within the route.</p>


```csharp
public string ToMeasureFieldName { get; }
```


