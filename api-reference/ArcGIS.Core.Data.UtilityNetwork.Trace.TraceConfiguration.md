# TraceConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">The TraceConfiguration object defines a set of input parameters to a tracing operation.</p>


## Object Signature

```csharp
public class TraceConfiguration
```


## Members

### TraceConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Creates a new instance of the TraceConfiguration class.</p>


```csharp
public TraceConfiguration()
```
### AllowIndeterminateFlow

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether features with indeterminate flow will be traced.
The default value is true.</p>


```csharp
public bool AllowIndeterminateFlow { get; set; }
```
### DomainNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.DomainNetwork" data-throw-if-not-resolved="false"></xref> from which to start the trace.</p>


```csharp
public DomainNetwork DomainNetwork { get; set; }
```
### Filter

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Defines filter criteria for the trace.</p>


```csharp
public Filter Filter { get; }
```
### Functions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">A list of Functions to compute while executing the trace.</p>


```csharp
public IReadOnlyList<Function> Functions { get; set; }
```
### IgnoreBarriersAtStartingPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Indicates whether or not to ignore barriers at starting points.</p>


```csharp
public bool IgnoreBarriersAtStartingPoints { get; set; }
```
### IncludeBarriersWithResults

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Determines whether or not the elements that stop the trace are included in the trace results.</p>


```csharp
public bool IncludeBarriersWithResults { get; set; }
```
### IncludeContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Indicates whether to include containers of trace results as additional results.</p>


```csharp
public bool IncludeContainers { get; set; }
```
### IncludeContent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Indicates whether to include content of container trace results as additional results.</p>


```csharp
public bool IncludeContent { get; set; }
```
### IncludeIsolatedFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">When used in conjunction with the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.IsolationTracer" data-throw-if-not-resolved="false"></xref>, this option determines whether isolated features are returned in the trace results.</p>


```csharp
public bool IncludeIsolatedFeatures { get; set; }
```
### IncludeStructures

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Indicates whether to include structures attached to results as additional results.</p>


```csharp
public bool IncludeStructures { get; set; }
```
### IncludeUpToFirstSpatialContainer

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Specifies whether the containers returned will be limited to only those encountered up to, and including, the first spatial container
for each network element in the trace results. If no spatial containers are encountered but nonspatial containers are present for a
given network element, all nonspatial containers will be included in the results. This parameter is only available when <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.IncludeContainers" data-throw-if-not-resolved="false"></xref> is true.</p>


```csharp
public bool IncludeUpToFirstSpatialContainer { get; set; }
```
### InferConnectivity

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether trace will infer the connection even if there is no physical connection.</p>


```csharp
public bool InferConnectivity { get; set; }
```
### MaxHops

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating the maximum number of hops.</p>


```csharp
public int MaxHops { get; set; }
```
### NumPaths

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating the number of paths.</p>


```csharp
public int NumPaths { get; set; }
```
### OutputAssetTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">A list of <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> objects to indicate inclusion in trace results.</p>


```csharp
public IReadOnlyList<AssetType> OutputAssetTypes { get; set; }
```
### OutputCondition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">A conditional expression that determines which rows should be included in the trace results.</p>


```csharp
public Condition OutputCondition { get; set; }
```
### Propagators

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">A list of Propagators to execute while performing the trace.</p>


```csharp
public IReadOnlyList<Propagator> Propagators { get; set; }
```
### ShortestPathNetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> used to calculate the shortest path when using the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.ShortestPathTracer" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public NetworkAttribute ShortestPathNetworkAttribute { get; set; }
```
### SourceTier

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref> that is used as the start of the trace.</p>


```csharp
public Tier SourceTier { get; set; }
```
### SynthesizeGeometries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether geometries will be created for associations and edge objects traversed as part of a trace operation.</p>


```csharp
public bool SynthesizeGeometries { get; set; }
```
### TargetTier

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref> that is used to constrain the tiers returned by the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.DownstreamTracer" data-throw-if-not-resolved="false"></xref> traces.</p>


```csharp
public Tier TargetTier { get; set; }
```
### Traversability

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Defines the criteria for stopping further traversal during a trace.</p>


```csharp
public Traversability Traversability { get; }
```
### UseDigitizedDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether trace will use the flow direction.
The default value is false.</p>


```csharp
public bool UseDigitizedDirection { get; set; }
```
### ValidateConsistency

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Indicates whether to validate network consistency as part of the trace operation.</p>


```csharp
public bool ValidateConsistency { get; set; }
```
### ValidateLocatability

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.yml" sourcestartlinenumber="1">Specifies whether an error will be returned during a trace if nonspatial junction or edge objects are encountered without the necessary containment,
attachment, or connectivity association in their association hierarchy of the traversed objects. This parameter ensures that nonspatial objects returned
by a trace or update subnetwork operation can be located through an association with features or other locatable objects.</p>


```csharp
public bool ValidateLocatability { get; set; }
```


