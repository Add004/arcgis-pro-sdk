# CircuitPath

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CircuitPath.yml" sourcestartlinenumber="1">Represents the path of physical or virtual circuits in a telecom domain network.</p>


## Object Signature

```csharp
public sealed class CircuitPath
```


## Members

### Circuit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CircuitPath.yml" sourcestartlinenumber="1"><xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.CircuitPath.Circuit" data-throw-if-not-resolved="false"></xref> represents a physical, non-sectioned circuit or a sectioned circuit.&quot;/&gt;</p>


```csharp
public Circuit Circuit { get; }
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CircuitPath.yml" sourcestartlinenumber="1">Represents geometry of a circuit.</p>


```csharp
public Geometry Geometry { get; }
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CircuitPath.yml" sourcestartlinenumber="1">Represents path of a physical, non-sectioned circuit.</p>


```csharp
public TracePath Path { get; }
```
### SectionPaths

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.CircuitPath.yml" sourcestartlinenumber="1">Key-value pairs representing the paths of sections in a sectioned circuit.</p>


```csharp
public IReadOnlyDictionary<int, TracePath> SectionPaths { get; }
```


