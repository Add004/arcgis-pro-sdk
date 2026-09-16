# UnitQueryResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitQueryResult.yml" sourcestartlinenumber="1">Represents the result of a query for <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> values within an equipment container (<xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier" data-throw-if-not-resolved="false"></xref>).</p>


## Object Signature

```csharp
public sealed class UnitQueryResult
```


## Members

### Container

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitQueryResult.yml" sourcestartlinenumber="1">Represents an equipment container (<xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitIdentifier" data-throw-if-not-resolved="false"></xref>), such as a rack or a switch, that contains the <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> values.</p>


```csharp
public UnitIdentifier Container { get; }
```
### UnitRanges

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitQueryResult.yml" sourcestartlinenumber="1">Gets the set of <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.UnitRange" data-throw-if-not-resolved="false"></xref> values contained within the container, such as ports (content) in a switch or slots (container) in a rack.</p>


```csharp
public IReadOnlyList<UnitRange> UnitRanges { get; }
```


