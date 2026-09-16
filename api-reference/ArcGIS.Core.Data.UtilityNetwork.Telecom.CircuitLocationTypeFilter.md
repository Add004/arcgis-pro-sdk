# CircuitLocationTypeFilter

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocationTypeFilter.yml" sourcestartlinenumber="1">Specifies the type of query to be performed on a circuit's location.</p>


## Object Signature

```csharp
public enum CircuitLocationTypeFilter
```


## Members

### All

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocationTypeFilter.yml" sourcestartlinenumber="1">Query for circuits that start at, stop at, or pass through a location.</p>


```csharp
All = 4
```
### NotApplicable

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocationTypeFilter.yml" sourcestartlinenumber="1">The query does not involve a circuit location.</p>


```csharp
NotApplicable = 1
```
### Start

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocationTypeFilter.yml" sourcestartlinenumber="1">Query for circuits that start at a specific location.</p>


```csharp
Start = 2
```
### Stop

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitLocationTypeFilter.yml" sourcestartlinenumber="1">Query for circuits that stop at a specific location.</p>


```csharp
Stop = 3
```


