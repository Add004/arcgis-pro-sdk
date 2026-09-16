# ExtendFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">Extend flag options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.Extend(ArcGIS.Core.Geometry.Polyline%2cArcGIS.Core.Geometry.Polyline%2cArcGIS.Core.Geometry.ExtendFlags)" data-throw-if-not-resolved="false"></xref> function.</p>


## Object Signature

```csharp
public enum ExtendFlags
```


## Members

### Default

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">By default, extension considers both ends of parts. The old ends remain and new points are added at the extended ends. The new points have attributes that are extrapolated from adjacent existing segments.</p>


```csharp
Default = 0
```
### KeepEndAttributes

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">If an extension is performed at an end, do not extrapolate the end-segment's attributes for the new point. Instead, make its attributes the same as the current end. Incompatible with NoEndAttributes.</p>


```csharp
KeepEndAttributes = 2
```
### NoEndAttributes

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">If an extension is performed at an end, do not extrapolate the end-segment's attributes for the new point. Instead, make its attributes be empty. Incompatible with KeepEndAttributes.</p>


```csharp
NoEndAttributes = 4
```
### NoExtendAtFrom

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">Do not extend the 'from' end of any part.</p>


```csharp
NoExtendAtFrom = 8
```
### NoExtendAtTo

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">Do not extend the 'to' end of any part.</p>


```csharp
NoExtendAtTo = 16
```
### RelocateEnds

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">If an extension is performed at an end, relocate the end point to the new position instead of leaving the old point and adding a new point at the new position.</p>


```csharp
RelocateEnds = 1
```


