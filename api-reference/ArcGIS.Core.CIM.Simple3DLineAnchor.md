# Simple3DLineAnchor

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.Simple3DLineAnchor.yml" sourcestartlinenumber="1">Defines the vertical anchor used to render the simple 3D line style in relation to the ground in 3D.
This property is ignored for the Strip style which is drawn flat upon the surface, and for the Wall
style which always uses a Bottom anchor.</p>


## Object Signature

```csharp
public enum Simple3DLineAnchor
```


## Members

### Bottom

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.Simple3DLineAnchor.yml" sourcestartlinenumber="1">The 3D line style is rendered above the ground as the vertical anchor is set to the bottom of the style.</p>


```csharp
Bottom = 1
```
### Center

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.Simple3DLineAnchor.yml" sourcestartlinenumber="1">The center of the 3D line style is vertically aligned with the ground.
The 3D line style is rendered both above and under the ground as a result.</p>


```csharp
Center = 0
```
### Top

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.Simple3DLineAnchor.yml" sourcestartlinenumber="1">The 3D line style is rendered under the ground as the vertical anchor is set to the top of the style.</p>


```csharp
Top = 2
```


