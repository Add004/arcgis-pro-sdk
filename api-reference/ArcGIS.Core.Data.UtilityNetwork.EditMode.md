# EditMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.EditMode.yml" sourcestartlinenumber="1">The editing mode used when updating subnetworks.</p>


## Object Signature

```csharp
public enum EditMode
```


## Members

### WithEventing

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.EditMode.yml" sourcestartlinenumber="1">Eventing will be used for subnetwork updates.
This edit mode will execute geodatabase behavior (for example, attribute rules, editor tracking, and so on) when the subnetwork is updated.</p>


```csharp
WithEventing = 2
```
### WithoutEventing

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.EditMode.yml" sourcestartlinenumber="1">Eventing will not be used for subnetwork updates. This edit mode only updates the subnetwork name and propagated values.</p>


```csharp
WithoutEventing = 1
```


