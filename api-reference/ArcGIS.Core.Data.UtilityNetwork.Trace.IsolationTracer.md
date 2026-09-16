# IsolationTracer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IsolationTracer.yml" sourcestartlinenumber="1">The IsolationTracer class identifies features that can isolate a specific section of a network</p>


## Object Signature

```csharp
public class IsolationTracer : Tracer
```

## Remarks

<ul>
  <li>
    The isolation trace requires that at least one <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Filter" data-throw-if-not-resolved="false"></xref> barrier is set in the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration" data-throw-if-not-resolved="false"></xref>. Typically this filter identifies those features that 
    isolate the section of network (e.g., valves). 
    </li>
  <li>
    The <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration.IncludeIsolatedFeatures" data-throw-if-not-resolved="false"></xref>  property can be used with the isolation trace to include the isolated features with the trace results.  If set to <b>False</b>,
    the default, only the isolating features (e.g., valves) are returned.
    </li>
</ul>


## Members

### Export(Uri, TraceArgument, TraceExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IsolationTracer.yml" sourcestartlinenumber="1">Executes an isolation trace and exports the results to a json file.</p>


```csharp
public override void Export(Uri outputJsonPath, TraceArgument traceArgument, TraceExportOptions traceExportOptions)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IsolationTracer.yml" sourcestartlinenumber="1">The name of the Tracer object</p>


```csharp
public override string Name { get; }
```
### Trace(TraceArgument)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IsolationTracer.yml" sourcestartlinenumber="1">Executes an isolation trace.</p>


```csharp
public override IReadOnlyList<Result> Trace(TraceArgument traceArgument)
```
### Trace(TraceArgument, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.IsolationTracer.yml" sourcestartlinenumber="1">Executes an isolation trace.</p>


```csharp
public override IReadOnlyList<Result> Trace(TraceArgument traceArgument, ServiceSynchronizationType serviceSynchronizationType)
```


