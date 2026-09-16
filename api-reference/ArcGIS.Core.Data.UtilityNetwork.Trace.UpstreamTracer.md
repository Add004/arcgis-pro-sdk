# UpstreamTracer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer.yml" sourcestartlinenumber="1">The UpstreamTracer class performs a upstream trace.</p>


## Object Signature

```csharp
public class UpstreamTracer : Tracer
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer.yml" sourcestartlinenumber="1">For subnetworks with sources, upstream is defined as paths that lead to a source.  For subnetworks with sinks, upstream is defined as paths that do not lead to a sink.</p>


## Members

### Export(Uri, TraceArgument, TraceExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer.yml" sourcestartlinenumber="1">Executes an upstream trace and exports the results to a json file.</p>


```csharp
public override void Export(Uri outputJsonPath, TraceArgument traceArgument, TraceExportOptions traceExportOptions)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer.yml" sourcestartlinenumber="1">The name of the Tracer object.</p>


```csharp
public override string Name { get; }
```
### Trace(TraceArgument)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer.yml" sourcestartlinenumber="1">Executes an upstream trace.</p>


```csharp
public override IReadOnlyList<Result> Trace(TraceArgument traceArgument)
```
### Trace(TraceArgument, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.UpstreamTracer.yml" sourcestartlinenumber="1">Executes an upstream trace.</p>


```csharp
public override IReadOnlyList<Result> Trace(TraceArgument traceArgument, ServiceSynchronizationType serviceSynchronizationType)
```


