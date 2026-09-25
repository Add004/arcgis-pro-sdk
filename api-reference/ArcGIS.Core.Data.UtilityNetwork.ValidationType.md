# ValidationType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationType.yml" sourcestartlinenumber="1">Specifies the type of validation performed when validating a utility network.</p>


## Object Signature

```csharp
public enum ValidationType
```


## Members

### ForceRebuild

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationType.yml" sourcestartlinenumber="1">Ignores dirty areas and rebuilds the network topology for everything in the given extent. It should be used when a repair validate fails.</p>


```csharp
ForceRebuild = 2
```
### Normal

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationType.yml" sourcestartlinenumber="1">Normal. Validates the utility network topology within the provided extent.</p>


```csharp
Normal = 0
```
### Repair

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationType.yml" sourcestartlinenumber="1">Uses the extent of the dirty areas in the given extent to build the network topology.  It should be used when a normal validate fails.</p>


```csharp
Repair = 1
```


