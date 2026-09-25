# PlacementClip

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.PlacementClip.yml" sourcestartlinenumber="1">Options for how the markers should be clipped at the polygon boundary.</p>


## Object Signature

```csharp
public enum PlacementClip
```


## Members

### ClipAtBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementClip.yml" sourcestartlinenumber="1">Markers are clipped at the boundary of the polygon.</p>


```csharp
ClipAtBoundary = 0
```
### DoNotClip

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementClip.yml" sourcestartlinenumber="1">Markers are not clipped and may extend past the boundary of the polygon.</p>


```csharp
DoNotClip = 3
```
### DoNotTouchBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementClip.yml" sourcestartlinenumber="1">Markers are not drawn if they touch the boundary of the polygon.</p>


```csharp
DoNotTouchBoundary = 2
```
### RemoveIfCenterOutsideBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementClip.yml" sourcestartlinenumber="1">Markers are not drawn if their center falls outside of the polygon.</p>


```csharp
RemoveIfCenterOutsideBoundary = 1
```


