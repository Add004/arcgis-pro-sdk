# Result

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Result.yml" sourcestartlinenumber="1">The Result object returns information from a trace.</p>


## Object Signature

```csharp
public abstract class Result
```


## Members

### Result(NearestNeighborResult)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Result.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Result</code> class.</p>


```csharp
protected Result(NearestNeighborResult nearestNeighborResult)
```
### NearestNeighborResult

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.Result.yml" sourcestartlinenumber="1">Returns whether the <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor" data-throw-if-not-resolved="false"></xref> filter returned the correct number of results.</p>


```csharp
public NearestNeighborResult NearestNeighborResult { get; }
```


