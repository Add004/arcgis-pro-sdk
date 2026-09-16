# TracePath

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TracePath.yml" sourcestartlinenumber="1">Represents traversed information during a path or circuit trace.</p>


## Object Signature

```csharp
public class TracePath
```


## Members

### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TracePath.yml" sourcestartlinenumber="1">Represents geometry of a path.</p>


```csharp
public Geometry Geometry { get; }
```
### PathConnectivities

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TracePath.yml" sourcestartlinenumber="1">The list of junction and edges along the path.</p>


```csharp
public IReadOnlyList<PathConnectivity> PathConnectivities { get; }
```
### StartLocation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TracePath.yml" sourcestartlinenumber="1">The start location of the path.</p>


```csharp
public Element StartLocation { get; }
```
### StopLocation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.TracePath.yml" sourcestartlinenumber="1">The stop location of the path.</p>


```csharp
public Element StopLocation { get; }
```


