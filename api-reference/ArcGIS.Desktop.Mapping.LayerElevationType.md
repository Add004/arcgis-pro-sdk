# LayerElevationType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Specifies the available elevation modes or &quot;types&quot; for layers.</p>


## Object Signature

```csharp
public enum LayerElevationType
```


## Members

### AtAbsoluteHeight

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Features that occur at a constant height above a datum, regardless of ground elevation.</p>


```csharp
AtAbsoluteHeight = 5
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">No applicable elevation type</p>


```csharp
None = 0
```
### OnCustomSurface

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Features that occur on a surface not represented by ground level.</p>


```csharp
OnCustomSurface = 2
```
### OnGround

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Features that are situated at ground level.</p>


```csharp
OnGround = 1
```
### RelativeToCustomSurface

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Features are relative to a custom surface.</p>


```csharp
RelativeToCustomSurface = 4
```
### RelativeToGround

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Features that are placed at a known height above the ground.</p>


```csharp
RelativeToGround = 3
```
### RelativeToScene

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerElevationType.yml" sourcestartlinenumber="1">Features will be vertically offset from the scene.</p>


```csharp
RelativeToScene = 6
```


