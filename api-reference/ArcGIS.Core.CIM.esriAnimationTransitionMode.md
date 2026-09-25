# esriAnimationTransitionMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.esriAnimationTransitionMode.yml" sourcestartlinenumber="1">Define the type of algorithm used to calculate transitions between animation camera keyframes.</p>


## Object Signature

```csharp
public enum esriAnimationTransitionMode
```


## Members

### esriAnimationTransitionModeAuto

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriAnimationTransitionMode.yml" sourcestartlinenumber="1">Calculate the path between camera keyframes using a geodesic algorithm in global scene views and a cartesian algorithm in all other views.</p>


```csharp
esriAnimationTransitionModeAuto = 0
```
### esriAnimationTransitionModeCartesian

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriAnimationTransitionMode.yml" sourcestartlinenumber="1">Calculate the path between camera keyframes using a cartesian algorithm.</p>


```csharp
esriAnimationTransitionModeCartesian = 1
```
### esriAnimationTransitionModeGeodesic

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriAnimationTransitionMode.yml" sourcestartlinenumber="1">Calculate the path between camera keyframes using a geodesic algorithm.</p>


```csharp
esriAnimationTransitionModeGeodesic = 2
```


