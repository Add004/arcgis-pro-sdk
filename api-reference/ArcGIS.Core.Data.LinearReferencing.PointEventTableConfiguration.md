# PointEventTableConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventTableConfiguration.yml" sourcestartlinenumber="1">Describes a point event table to hold events' information as the results of <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo.LocateFeatures(ArcGIS.Core.Data.FeatureClass%2cSystem.Double%2cArcGIS.Core.Data.LinearReferencing.EventTableConfiguration)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class PointEventTableConfiguration : EventTableConfiguration
```


## Members

### PointEventTableConfiguration(string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventTableConfiguration.yml" sourcestartlinenumber="1">Construct an object to describe a point event table to hold events' information, <xref href="ArcGIS.Core.Data.LinearReferencing.EventInfo" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public PointEventTableConfiguration(string eventTableName, string routeIDFieldName, string measureFieldName)
```
### EventType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventTableConfiguration.yml" sourcestartlinenumber="1">Gets the event type, <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventTableConfiguration.EventType" data-throw-if-not-resolved="false"></xref></p>


```csharp
public override EventType EventType { get; }
```
### MeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventTableConfiguration.yml" sourcestartlinenumber="1">Gets the name of the field containing the measure value associated with the point event.</p>


```csharp
public string MeasureFieldName { get; }
```


