# GradientAlignment

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.GradientAlignment.yml" sourcestartlinenumber="1">Gradient alignment types.</p>


## Object Signature

```csharp
public enum GradientAlignment
```


## Members

### AlongLine

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GradientAlignment.yml" sourcestartlinenumber="1">Along line - Distributes the color ramp linearly along the line, following the curvature of the line.</p>


```csharp
AlongLine = 3
```
### Buffered

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GradientAlignment.yml" sourcestartlinenumber="1">Buffered - Distributes the color ramp along the line's geometry from the outside in (similar to the effect of creating a buffer of the line, then using the &quot;buffer&quot; fill type).</p>


```csharp
Buffered = 0
```
### Left

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GradientAlignment.yml" sourcestartlinenumber="1">Left - Progresses the color ramp from the line's centerline to the outside edge on the left. The gradient will follow any curvature in the line's geometry.</p>


```csharp
Left = 1
```
### Right

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GradientAlignment.yml" sourcestartlinenumber="1">Right - Progresses the color ramp from the line's centerline to the outside edge on the right. The gradient will follow any curvature in the line's geometry.</p>


```csharp
Right = 2
```


