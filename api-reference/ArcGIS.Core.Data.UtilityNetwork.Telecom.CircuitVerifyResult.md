# CircuitVerifyResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyResult.yml" sourcestartlinenumber="1">Represents the result for an individual circuit that participated in a <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.Verify(System.Collections.Generic.IEnumerable%7bSystem.String%7d%2cArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions)" data-throw-if-not-resolved="false"></xref> operation.</p>


## Object Signature

```csharp
public sealed class CircuitVerifyResult
```


## Members

### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyResult.yml" sourcestartlinenumber="1">The geometry returned from the verify operation.</p>


```csharp
public Geometry Geometry { get; }
```
### HasError

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyResult.yml" sourcestartlinenumber="1">Indicates whether an error occurred during verification.</p>


```csharp
public bool HasError { get; }
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyResult.yml" sourcestartlinenumber="1">The description of the error, if there is one.</p>


```csharp
public string Message { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyResult.yml" sourcestartlinenumber="1">The name of the circuit.</p>


```csharp
public string Name { get; }
```


