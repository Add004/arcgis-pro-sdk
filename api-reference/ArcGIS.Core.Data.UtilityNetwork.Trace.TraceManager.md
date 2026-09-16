# TraceManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceManager.yml" sourcestartlinenumber="1">The TraceManager class provides access to <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer" data-throw-if-not-resolved="false"></xref> objects.</p>


## Object Signature

```csharp
public sealed class TraceManager : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceManager.yml" sourcestartlinenumber="1">Objects of this class are obtained through a call to <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.GetTraceManager" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### GetNamedTraceConfigurations(NamedTraceConfigurationQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceManager.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NamedTraceConfiguration" data-throw-if-not-resolved="false"></xref>s associated with a <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NamedTraceConfiguration> GetNamedTraceConfigurations(NamedTraceConfigurationQuery parameters)
```
### GetTracer(NamedTraceConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceManager.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer" data-throw-if-not-resolved="false"></xref> instance based on the <code class="paramref">namedTraceConfiguration</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tracer GetTracer(NamedTraceConfiguration namedTraceConfiguration)
```
### GetTracer&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TraceManager.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Tracer" data-throw-if-not-resolved="false"></xref> instance of type <code class="typeparamref">T</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetTracer<T>() where T : Tracer
```


