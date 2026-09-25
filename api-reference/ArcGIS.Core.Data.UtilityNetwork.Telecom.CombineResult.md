# CombineResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombineResult.yml" sourcestartlinenumber="1">Provides information about the results of a call to ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.Combine(IEnumerable&lt;TelecomElement&gt;).</p>


## Object Signature

```csharp
public class CombineResult
```


## Members

### CombinedElement

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombineResult.yml" sourcestartlinenumber="1">The combined element.</p>


```csharp
public TelecomElement CombinedElement { get; }
```
### DeletedGlobalIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombineResult.yml" sourcestartlinenumber="1">The GlobalIDs of the deleted elements.</p>


```csharp
public IReadOnlyList<Guid> DeletedGlobalIDs { get; }
```


