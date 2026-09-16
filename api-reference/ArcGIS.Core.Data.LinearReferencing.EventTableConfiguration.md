# EventTableConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Describes an event table to hold events' information as the results of <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo.LocateFeatures(ArcGIS.Core.Data.FeatureClass%2cSystem.Double%2cArcGIS.Core.Data.LinearReferencing.EventTableConfiguration)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class EventTableConfiguration
```


## Members

### EventTableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Gets the event table name.</p>


```csharp
public string EventTableName { get; }
```
### EventType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Gets the event type, <xref href="ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.EventType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public abstract EventType EventType { get; }
```
### KeepAllFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Gets whether all the attributes from the feature class that intersect with <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo" data-throw-if-not-resolved="false"></xref> will be included in the result.</p>


```csharp
public bool KeepAllFields { get; set; }
```
### MDirectionOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Gets whether the offset distance calculation is based on the m-direction or the digitized direction.<i>Reserved for future usage</i>.</p>


```csharp
public bool MDirectionOffset { get; set; }
```
### RouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Gets the name of the field that uniquely identifies each route.</p>


```csharp
public string RouteIDFieldName { get; }
```


