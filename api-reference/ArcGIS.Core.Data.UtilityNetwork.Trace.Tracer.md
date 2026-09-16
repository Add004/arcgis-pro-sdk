# Tracer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">Tracer is an abstract base class that provides tracing capabilities.</p>


## Object Signature

```csharp
public abstract class Tracer
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">ArcGIS Pro ships with a number of pre-defined Tracer objects.  Additional custom traces can be defined by subclassing the Tracer object.<br>
Tracer objects are created and obtained by calling TraceManager.GetTracer().</p>


## Members

### Tracer(UtilityNetwork)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
protected Tracer(UtilityNetwork utilityNetwork)
```
### Export(Uri, TraceArgument, TraceExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">Exports trace results into a JSON file.</p>


```csharp
public abstract void Export(Uri outputJsonPath, TraceArgument traceArgument, TraceExportOptions traceExportOptions)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">The name of the Tracer object.</p>


```csharp
public abstract string Name { get; }
```
### Trace(TraceArgument)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">Executes a trace.</p>


```csharp
public abstract IReadOnlyList<Result> Trace(TraceArgument traceArgument)
```
### Trace(TraceArgument, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">Executes a trace.</p>


```csharp
public abstract IReadOnlyList<Result> Trace(TraceArgument traceArgument, ServiceSynchronizationType serviceSynchronizationType)
```
### UtilityNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.yml" sourcestartlinenumber="1">Returns the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer.UtilityNetwork" data-throw-if-not-resolved="false"></xref> object used to create the Tracer.</p>


```csharp
public UtilityNetwork UtilityNetwork { get; }
```


