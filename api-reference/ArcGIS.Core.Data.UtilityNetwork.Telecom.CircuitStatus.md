# CircuitStatus

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitStatus.yml" sourcestartlinenumber="1">Specifies the status of a circuit in the utility network.</p>


## Object Signature

```csharp
public enum CircuitStatus
```


## Members

### Clean

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitStatus.yml" sourcestartlinenumber="1">The circuit verify has been run subsequent to any edits made to this circuit, and the circuit is clean.</p>


```csharp
Clean = 0
```
### Deleted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitStatus.yml" sourcestartlinenumber="1">The circuit has been logically deleted.</p>


```csharp
Deleted = 3
```
### Dirty

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitStatus.yml" sourcestartlinenumber="1">Changes have been made to the circuit, but verify has not been run on the circuit.</p>


```csharp
Dirty = 1
```
### Invalid

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitStatus.yml" sourcestartlinenumber="1">Circuit has been updated, and error conditions exist in the circuit. It cannot be verified until the errors are resolved.</p>


```csharp
Invalid = 2
```


