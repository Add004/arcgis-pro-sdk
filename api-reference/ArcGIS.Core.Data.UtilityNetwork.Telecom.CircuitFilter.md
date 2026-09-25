# CircuitFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Represents a filter used to query for circuits.</p>


## Object Signature

```csharp
public sealed class CircuitFilter
```


## Members

### CircuitFilter(IEnumerable&lt;CircuitLocation&gt;, CircuitLocationTypeFilter)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Constructs a filter based on circuit locations.</p>


```csharp
public CircuitFilter(IEnumerable<CircuitLocation> locations, CircuitLocationTypeFilter locationType)
```
### CircuitFilter(IEnumerable&lt;Guid&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Constructs a filter based on circuit global IDs.</p>


```csharp
public CircuitFilter(IEnumerable<Guid> globalIDs)
```
### CircuitFilter(IEnumerable&lt;string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Constructs a filter based on circuit names.</p>


```csharp
public CircuitFilter(IEnumerable<string> circuitNames)
```
### GlobalIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">The global IDs of the circuits.</p>


```csharp
public IReadOnlyList<Guid> GlobalIDs { get; }
```
### Hierarchy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Indicates if providers, consumers, or both should be included.</p>


```csharp
public CircuitHierarchy Hierarchy { get; set; }
```
### LocationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Specifies whether the locations are starting at, stopping at, or along a circuit.</p>


```csharp
public CircuitLocationTypeFilter LocationType { get; }
```
### Locations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">The locations of the circuits.</p>


```csharp
public IReadOnlyList<CircuitLocation> Locations { get; }
```
### Names

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">The names of the circuits.</p>


```csharp
public IReadOnlyList<string> Names { get; }
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CircuitFilter.yml" sourcestartlinenumber="1">Specifies whether to include circuits based on status.</p>


```csharp
public CircuitStatusFilter Status { get; set; }
```


