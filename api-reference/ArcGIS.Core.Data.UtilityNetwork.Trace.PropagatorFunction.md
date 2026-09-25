# PropagatorFunction

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.PropagatorFunction.yml" sourcestartlinenumber="1">The functions that can be used with <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.Propagator" data-throw-if-not-resolved="false"></xref>s.</p>


## Object Signature

```csharp
public enum PropagatorFunction
```


## Members

### BitwiseAnd

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.PropagatorFunction.yml" sourcestartlinenumber="1">The network attribute value of the current element is bitwise-anded with the network attribute value propagated from the source.</p>


```csharp
BitwiseAnd = 1
```
### Max

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.PropagatorFunction.yml" sourcestartlinenumber="1">The network attribute value of the current element is compared against the network attribute value propagated from the source- the maximum of these values is propagated further downstream.</p>


```csharp
Max = 3
```
### Min

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.PropagatorFunction.yml" sourcestartlinenumber="1">The network attribute value of the current element is compared against the network attribute value propagated from the source- the minimum of these values is propagated further downstream.</p>


```csharp
Min = 2
```


