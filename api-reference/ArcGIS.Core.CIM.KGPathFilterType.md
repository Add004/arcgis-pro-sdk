# KGPathFilterType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFilterType.yml" sourcestartlinenumber="1">Specifies the filter type of a path filter used in filtered find paths.</p>


## Object Signature

```csharp
public enum KGPathFilterType
```


## Members

### Exclude

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFilterType.yml" sourcestartlinenumber="1">The filtered find paths algorithm will ignore paths that contain excluded types (type is not active).</p>


```csharp
Exclude = 1
```
### IncludeOnly

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFilterType.yml" sourcestartlinenumber="1">The filtered find paths algorithm will only consider paths which contain included types (type is active).
If a path filter does not use the include only option, all types are active.</p>


```csharp
IncludeOnly = 0
```
### MandatoryWaypoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFilterType.yml" sourcestartlinenumber="1">The filtered find paths algorithm will only consider paths passing through the all the mandatory waypoints.</p>


```csharp
MandatoryWaypoint = 2
```
### OptionalWaypoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGPathFilterType.yml" sourcestartlinenumber="1">The filtered find paths algorithm will only consider paths passing through at least one of the optional waypoints.</p>


```csharp
OptionalWaypoint = 3
```


