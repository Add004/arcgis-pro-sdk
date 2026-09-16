# LineOfSightResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">A class to contain the results of running <xref href="ArcGIS.Desktop.Mapping.SurfaceLayer.GetLineOfSight(ArcGIS.Desktop.Mapping.LineOfSightParams)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class LineOfSightResult
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">The output line of sight is divided into visible and invisible portions along the input sight line running from
the <xref href="ArcGIS.Desktop.Mapping.LineOfSightParams.ObserverPoint" data-throw-if-not-resolved="false"></xref> to the <xref href="ArcGIS.Desktop.Mapping.LineOfSightParams.TargetPoint" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### InvisibleLine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">Gets the invisible part(s), if any, of the surface profile, from the
perspective of the observer point when looking towards the target point.</p>


```csharp
public Polyline InvisibleLine { get; }
```
### IsTargetVisibleFromInvisibleLine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">Gets whether the target is visible from the invisible line.</p>


```csharp
public bool IsTargetVisibleFromInvisibleLine { get; }
```
### IsTargetVisibleFromObserverPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">Gets whether the target point is visible from the observer point.</p>


```csharp
public bool IsTargetVisibleFromObserverPoint { get; }
```
### IsTargetVisibleFromVisibleLine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">Gets whether the target is visible from the visible line.</p>


```csharp
public bool IsTargetVisibleFromVisibleLine { get; }
```
### ObstructionPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">Gets the location, if any, of the first obstruction on the
observer's sight line to the target.</p>


```csharp
public MapPoint ObstructionPoint { get; }
```
### VisibleLine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSightResult.yml" sourcestartlinenumber="1">Gets the visible part(s), if any, of the surface profile, from the
perspective of the observer point when looking towards the target point.</p>


```csharp
public Polyline VisibleLine { get; }
```


