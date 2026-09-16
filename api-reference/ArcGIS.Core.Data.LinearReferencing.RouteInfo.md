# RouteInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Represents a route feature class's information, <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>. A route feature class is an M-enabled
polyline feature class containing a unique identifier attribute field.</p>


## Object Signature

```csharp
public sealed class RouteInfo
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">A route is any line feature, such as a street, highway, river, or pipe, that contains a unique identifier and a
system of measurement.
Routes are stored in an M-enabled feature class containing a unique identifier attribute field.
The M-values are used to measure the distance along a line feature.
Measures can be any unit of measurement, such as miles, meters, and time, and they are stored as  M-values on route vertices.</p>


## Members

### RouteInfo(FeatureClass, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public RouteInfo(FeatureClass routeFeatureClass, string routeIDFieldName)
```
### GetRouteFeatureClass()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Gets the feature class containing routes underlying the <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public FeatureClass GetRouteFeatureClass()
```
### LocateFeatures(FeatureClass, double, EventTableConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Computes the intersection between input features and route features and then stores the resulting route and measure information in a new event table as described by <code class="paramref">eventTableConfiguration</code>. The search radius defines how far a search will be done to find a target route.</p>


```csharp
public void LocateFeatures(FeatureClass featureClass, double searchRadius, EventTableConfiguration eventTableConfiguration)
```
### LocateFeatures(Selection, double, EventTableConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Computes the intersection between selected features and route features and then stores the resulting route and measure information in a new event table as described by <code class="paramref">eventTableConfiguration</code>.The search radius defines how far a search will be done to find a target route.</p>


```csharp
public void LocateFeatures(Selection selectedFeatures, double searchRadius, EventTableConfiguration eventTableConfiguration)
```
### RouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Gets the name of the field that uniquely identifies each route.</p>


```csharp
public string RouteIDFieldName { get; }
```


