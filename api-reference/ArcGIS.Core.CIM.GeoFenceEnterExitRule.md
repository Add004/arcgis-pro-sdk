# GeoFenceEnterExitRule

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.GeoFenceEnterExitRule.yml" sourcestartlinenumber="1">Rules to indicate whether a fence polygon has been entered or exited by the geometry from a feed.</p>


## Object Signature

```csharp
public enum GeoFenceEnterExitRule
```


## Members

### EnterContainsAndExitDoesNotContain

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeoFenceEnterExitRule.yml" sourcestartlinenumber="1">A fence polygon is entered when it contains a feed geometry and exited when it is no longer contained.</p>


```csharp
EnterContainsAndExitDoesNotContain = 1
```
### EnterContainsAndExitDoesNotIntersect

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeoFenceEnterExitRule.yml" sourcestartlinenumber="1">A fence polygon is entered when it contains a feed geometry and exited when it no longer intersects.</p>


```csharp
EnterContainsAndExitDoesNotIntersect = 0
```
### EnterIntersectsAndExitDoesNotIntersect

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeoFenceEnterExitRule.yml" sourcestartlinenumber="1">A fence polygon is entered when it intersects a feed geometry and exited when it no longer intersects.</p>


```csharp
EnterIntersectsAndExitDoesNotIntersect = 2
```


