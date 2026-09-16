# AltitudeMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.AltitudeMode.yml" sourcestartlinenumber="1">Relative to the ground.</p>


## Object Signature

```csharp
public enum AltitudeMode
```


## Members

### Absolute

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AltitudeMode.yml" sourcestartlinenumber="1">Sets the altitude of the coordinate relative to sea level, regardless of the actual elevation of the terrain beneath the element.</p>


```csharp
Absolute = 2
```
### ClampToGround

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AltitudeMode.yml" sourcestartlinenumber="1">Indicates to ignore an altitude specification and draw the graphic directly on the surface of the earth.</p>


```csharp
ClampToGround = 0
```
### RelativeToGround

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.AltitudeMode.yml" sourcestartlinenumber="1">Sets the altitude of the graphic relative to the actual ground elevation of a particular location.</p>


```csharp
RelativeToGround = 1
```


