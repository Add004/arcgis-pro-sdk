# FaceCulling3D

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.FaceCulling3D.yml" sourcestartlinenumber="1">The types of face culling.</p>


## Object Signature

```csharp
public enum FaceCulling3D
```


## Members

### Backface

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FaceCulling3D.yml" sourcestartlinenumber="1">Turns on back-face culling, eliminating those objects from view that face away from you.</p>


```csharp
Backface = 0
```
### FromGeometry

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FaceCulling3D.yml" sourcestartlinenumber="1">Turns on the feature's built-in face culling. This option is only applicable for multipatch features.</p>


```csharp
FromGeometry = 3
```
### Frontface

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FaceCulling3D.yml" sourcestartlinenumber="1">Turns on front-face culling, eliminating those objects from view that face you. Use this option to see through the front of an object.</p>


```csharp
Frontface = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FaceCulling3D.yml" sourcestartlinenumber="1">Turns off culling so you view both sides.</p>


```csharp
None = 2
```


