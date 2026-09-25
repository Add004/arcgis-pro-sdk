# FFPConfigurationWarning

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">Describes Filtered Find Paths configuration warnings.</p>


## Object Signature

```csharp
public enum FFPConfigurationWarning
```


## Members

### AllDestinationsAreExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">All destination entities are excluded,
hence no path will be found.</p>


```csharp
AllDestinationsAreExcluded = 2
```
### AllOptionalWaypointsAreExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">All optional waypoints are excluded,
hence no path will be found.</p>


```csharp
AllOptionalWaypointsAreExcluded = 3
```
### AllOriginsAreExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">All origin entities are excluded,
hence no path will be found.</p>


```csharp
AllOriginsAreExcluded = 1
```
### AtLeastOneMandatoryEntityWaypointIsExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">At least one mandatory entity waypoint is excluded,
hence no path will be found.</p>


```csharp
AtLeastOneMandatoryEntityWaypointIsExcluded = 4
```
### AtLeastOneMandatoryRelationshipWaypointIsExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">At least one mandatory relationship waypoint is excluded,
hence no path will be found.</p>


```csharp
AtLeastOneMandatoryRelationshipWaypointIsExcluded = 5
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">No warning.</p>


```csharp
None = 0
```
### ReachedMaxPathLength

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FFPConfigurationWarning.yml" sourcestartlinenumber="1">No path was found, but increasing or disabling the max path length could help find some paths.</p>


```csharp
ReachedMaxPathLength = 6
```


