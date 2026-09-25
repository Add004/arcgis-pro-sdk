# FFPNoPathExplanation

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">When Filtered Find Paths has found no path, this enum gives insights as to why no path was found.</p>


## Object Signature

```csharp
public enum FFPNoPathExplanation
```


## Members

### AllDestinationsAreExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.PathFilters" data-throw-if-not-resolved="false"></xref> have excluded all destination entities.</p>


```csharp
AllDestinationsAreExcluded = 2
```
### AllOptionalWaypointsAreExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.PathFilters" data-throw-if-not-resolved="false"></xref> have excluded all optional waypoints.</p>


```csharp
AllOptionalWaypointsAreExcluded = 3
```
### AllOriginsAreExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.PathFilters" data-throw-if-not-resolved="false"></xref> have excluded all origin entities.</p>


```csharp
AllOriginsAreExcluded = 1
```
### AtLeastOneMandatoryEntityWaypointIsExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.PathFilters" data-throw-if-not-resolved="false"></xref> have excluded at least one mandatory waypoint.</p>


```csharp
AtLeastOneMandatoryEntityWaypointIsExcluded = 4
```
### AtLeastOneMandatoryRelationshipWaypointIsExcluded

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.PathFilters" data-throw-if-not-resolved="false"></xref> have excluded at least one mandatory relationship waypoint.</p>


```csharp
AtLeastOneMandatoryRelationshipWaypointIsExcluded = 5
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">Either some paths have been found, or no path has been found but we have not encountered one of the situations described by the other values of this enum.</p>


```csharp
None = 0
```
### ReachedMaxPathLength

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.FFPNoPathExplanation.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.MaxPathLength" data-throw-if-not-resolved="false"></xref> has been reached. Longer paths may exist.</p>


```csharp
ReachedMaxPathLength = 6
```


