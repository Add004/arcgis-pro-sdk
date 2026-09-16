# Traversability

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Traversability.yml" sourcestartlinenumber="1">The Traversability class encapsulates all of the criteria that determines traversability in a utility network trace.</p>


## Object Signature

```csharp
public sealed class Traversability
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Traversability.yml" sourcestartlinenumber="1">The Traversability class is usually used with the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.Traversability" data-throw-if-not-resolved="false"></xref> property.</p>


## Members

### Barriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Traversability.yml" sourcestartlinenumber="1">A conditional expression which terminates traversal if it evaluates to True.</p>


```csharp
public Condition Barriers { get; set; }
```
### FunctionBarriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Traversability.yml" sourcestartlinenumber="1">A set of <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.FunctionBarrier" data-throw-if-not-resolved="false"></xref> objects.  If any of these objects evaluates to true, further traversal is terminated.</p>


```csharp
public IReadOnlyList<FunctionBarrier> FunctionBarriers { get; set; }
```
### Scope

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Traversability.yml" sourcestartlinenumber="1">Determines whether traversability criteria are evaluated on edges, junctions, or both.</p>


```csharp
public TraversabilityScope Scope { get; set; }
```


