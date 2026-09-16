# Monotonicity

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">Describes trends in the value of an attribute.
See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetMMonotonicity(ArcGIS.Core.Geometry.Multipart)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
[Flags]
public enum Monotonicity
```


## Members

### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">There is no monotonicity, for example, the geometry is empty.</p>


```csharp
None = 0
```
### ValueDecreases

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">The value decreases over some intervals.</p>


```csharp
ValueDecreases = 4
```
### ValueEmpty

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">There are some gaps in the value where it is NaN.</p>


```csharp
ValueEmpty = 8
```
### ValueIncreases

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">The value increases over some intervals.</p>


```csharp
ValueIncreases = 1
```
### ValueLevel

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">The value remains constant over some intervals.</p>


```csharp
ValueLevel = 2
```


