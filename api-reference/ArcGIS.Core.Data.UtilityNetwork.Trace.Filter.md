# Filter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">The Filter class encapsulates all of the criteria that determine filters in a utility network trace.</p>


## Object Signature

```csharp
public sealed class Filter
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">Filters are a mechanism to stop tracing when returning results.  They do not stop traversability to the controller.</p>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="3">For example, let's assume you want to write a trace to find the next upstream protective device in an electrical network.  You would do this by creating a <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.CategoryComparison" data-throw-if-not-resolved="false"></xref> object to stop
when a feature is found that is assigned the &quot;Protective Device&quot; category.</p>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="6">If you entered this CategoryComparison object into <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Traversability.Barriers" data-throw-if-not-resolved="false"></xref> then the trace would be unable to find a subnetwork controller to determine
which direction was upstream.  The correct way to implement this is by entering this CategoryComparison object into <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.Barriers" data-throw-if-not-resolved="false"></xref> property of the Filter object.</p>


## Members

### Barriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">A conditional expression which stops tracing if it evaluates to True.</p>


```csharp
public Condition Barriers { get; set; }
```
### BitsetNetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">Specifies that a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> stores a bitset, and this bitset should be used to filter results.</p>


```csharp
public NetworkAttribute BitsetNetworkAttribute { get; set; }
```
### FunctionBarriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">A set of <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier" data-throw-if-not-resolved="false"></xref> objects.  If any of these objects evaluates to true, further tracing is terminated.</p>


```csharp
public IReadOnlyList<FunctionBarrier> FunctionBarriers { get; set; }
```
### NearestNeighbor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">Provides nearest neighbor filter information.</p>


```csharp
public NearestNeighbor NearestNeighbor { get; set; }
```
### Scope

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Filter.yml" sourcestartlinenumber="1">Determines whether filter criteria are evaluated on edges, junctions, or both.</p>


```csharp
public TraversabilityScope Scope { get; set; }
```


