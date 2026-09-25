# SubcircuitState

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.SubcircuitState.yml" sourcestartlinenumber="1">Specifies the state of a subcircuit.</p>


## Object Signature

```csharp
public enum SubcircuitState
```


## Members

### Available

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.SubcircuitState.yml" sourcestartlinenumber="1">A subcircuit is available when it is neither consumed nor reserved.</p>


```csharp
Available = 0
```
### Consumed

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.SubcircuitState.yml" sourcestartlinenumber="1">A subcircuit is consumed when another circuit consumes it as a section of the circuit.</p>


```csharp
Consumed = 1
```
### Reserved

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.SubcircuitState.yml" sourcestartlinenumber="1">A subcircuit is reserved when the provider circuit reserves its subcircuit.</p>


```csharp
Reserved = 2
```


