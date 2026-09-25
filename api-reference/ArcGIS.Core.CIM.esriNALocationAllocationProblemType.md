# esriNALocationAllocationProblemType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Problem types for the Location-Allocation solver</p>


## Object Signature

```csharp
public enum esriNALocationAllocationProblemType
```


## Members

### esriNALAPTMaximizeAttendance

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses N facilities that will maximize the demand point weight allocated to the facilities assuming that the allocated demand weight decreases with increased network distance.</p>


```csharp
esriNALAPTMaximizeAttendance = 3
```
### esriNALAPTMaximizeCapacitatedCoverage

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses N facilities that will reach all demand points within a specified cutoff and subject to a per facility capacity constraint. The sum of weighted costs between the facilities and demand points will also be minimized.</p>


```csharp
esriNALAPTMaximizeCapacitatedCoverage = 6
```
### esriNALAPTMaximizeCoverage

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses N facilities that will reach all demand points within a specified cutoff. Once all demand points have been reached the sum of weighted costs between the facilities and demand points will be minimized.</p>


```csharp
esriNALAPTMaximizeCoverage = 1
```
### esriNALAPTMaximizeCoverageMinimizeFacilities

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses the minimum number of facilities necessary to reach all demand points. Solution facilities will minimize the sum of weighted costs between the facilities and demand points.</p>


```csharp
esriNALAPTMaximizeCoverageMinimizeFacilities = 2
```
### esriNALAPTMaximizeMarketShare

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses N facilities that will maximize the market share of weighted demand points assuming the presence of competitor facilities. Uses a Huff model.</p>


```csharp
esriNALAPTMaximizeMarketShare = 4
```
### esriNALAPTMinimizeWeightedImpedance

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses N facilities that will minimize the sum of weighted costs between the facilities and demand points (PMedian).</p>


```csharp
esriNALAPTMinimizeWeightedImpedance = 0
```
### esriNALAPTTargetMarketShare

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNALocationAllocationProblemType.yml" sourcestartlinenumber="1">Chooses the minimum number of facilities necessary to achieve the target marketshare of weighted demand points assuming the presence of competitor facilities. Uses a Huff model.</p>


```csharp
esriNALAPTTargetMarketShare = 5
```


