# KGPathFindingError

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">Describes errors related to the time value(s) of a time event.</p>


## Object Signature

```csharp
public enum KGPathFindingError
```


## Members

### ConfigurationHasTooManyInputEntities

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">The configuration has too many input entities.</p>


```csharp
ConfigurationHasTooManyInputEntities = 1
```
### ConfigurationIsTooComplex

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">The configuration is too complex, this generally occurs when too many mandatory waypoints are defined.</p>


```csharp
ConfigurationIsTooComplex = 2
```
### DurativeEventHasNoTime

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">A durative event has a null start time and a null end time.</p>


```csharp
DurativeEventHasNoTime = 4
```
### DurativeEventHasOneMissingTime

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">A durative event has either a null start time or a null end time.</p>


```csharp
DurativeEventHasOneMissingTime = 5
```
### DurativeEventHasSwappedTimes

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">A durative event start time is strictly greater than the end time.</p>


```csharp
DurativeEventHasSwappedTimes = 6
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">No error.</p>


```csharp
None = 0
```
### PropertyFilterSyntaxError

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">A property filter predicate has a syntax error.</p>


```csharp
PropertyFilterSyntaxError = 7
```
### PunctualEventHasNoTime

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFindingError.yml" sourcestartlinenumber="1">A punctual event has a null time.</p>


```csharp
PunctualEventHasNoTime = 3
```


