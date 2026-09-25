# CircuitVerifyOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions.yml" sourcestartlinenumber="1">Specifies options for the <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitManager.Verify(System.Collections.Generic.IEnumerable%7bSystem.String%7d%2cArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions)" data-throw-if-not-resolved="false"></xref> operation.</p>


## Object Signature

```csharp
public sealed class CircuitVerifyOptions
```


## Members

### CircuitVerifyOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public CircuitVerifyOptions()
```
### ForceVerify

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions.yml" sourcestartlinenumber="1">Specifies whether circuits are forcefully verified.</p>


```csharp
public bool ForceVerify { get; set; }
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions.yml" sourcestartlinenumber="1">Specifies whether verification uses the synchronous or asynchronous service endpoint.</p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions.yml" sourcestartlinenumber="1">Specifies the spatial reference used for synthesized geometries.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### SynthesizeGeometries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitVerifyOptions.yml" sourcestartlinenumber="1">Specifies whether synthesized geometries are returned in the verification results.</p>


```csharp
public bool SynthesizeGeometries { get; set; }
```


