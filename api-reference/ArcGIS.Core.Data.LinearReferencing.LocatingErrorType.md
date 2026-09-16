# LocatingErrorType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Specifies the error type associated with a row in the event table when determining the event's location along a route via the dynamic
segmentation process.</p>


## Object Signature

```csharp
public enum LocatingErrorType
```


## Members

### CannotFindExtent

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Could not find route location's shape; the from-measure and the to-measure are outside of the route measures.</p>


```csharp
CannotFindExtent = 6
```
### CannotFindLocation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Could not find route location's shape (the route has no M values or the route location's measures don't exist on the route).</p>


```csharp
CannotFindLocation = 5
```
### CannotFindRoute

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">The route does not exist.</p>


```csharp
CannotFindRoute = 3
```
### FromPartialMatch

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Could not find the entire route location's shape; the from-measure was outside of the route measure range.</p>


```csharp
FromPartialMatch = 7
```
### FromToPartialMatch

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Could not find the entire route location's shape; the from-measure and the to-measure were outside of the route measure range.</p>


```csharp
FromToPartialMatch = 11
```
### InvalidMeasure

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">At least one of the route location's measure values is invalid.</p>


```csharp
InvalidMeasure = 2
```
### InvalidRouteID

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">The route location's route ID is invalid (null, empty, or invalid value).</p>


```csharp
InvalidRouteID = 1
```
### MultipleLocations

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">More than one point location was found.</p>


```csharp
MultipleLocations = 12
```
### NullExtent

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">The from-measure is equal to the to-measure.</p>


```csharp
NullExtent = 13
```
### RouteMValuesNull

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">The route does not have M values or the M values are null.</p>


```csharp
RouteMValuesNull = 9
```
### RouteNotMAware

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">The route is not a polyline M aware.</p>


```csharp
RouteNotMAware = 10
```
### RouteShapeEmpty

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">The route does not have a shape or the shape is empty.</p>


```csharp
RouteShapeEmpty = 4
```
### ToPartialMatch

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Could not find the entire route location's shape; the to-measure was outside of the route measure range.</p>


```csharp
ToPartialMatch = 8
```


