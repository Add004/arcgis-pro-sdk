# DivideResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DivideResult.yml" sourcestartlinenumber="1">Provides information about the results of a call to ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.Divide(TelecomElement, IEnumerable&lt;short&gt;).</p>


## Object Signature

```csharp
public class DivideResult
```


## Members

### ConnectedEdges

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DivideResult.yml" sourcestartlinenumber="1">The edge objects returned when the divide operation targets a junction object. The list is empty when no connected edge objects are returned.</p>


```csharp
public IReadOnlyList<TelecomElement> ConnectedEdges { get; }
```
### DividedElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DivideResult.yml" sourcestartlinenumber="1">The divided elements.</p>


```csharp
public IReadOnlyList<TelecomElement> DividedElements { get; }
```


