# SnapResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnapResult.yml" sourcestartlinenumber="1">Represents how a vertex has been snapped in the current sketch.</p>


## Object Signature

```csharp
public sealed class SnapResult
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnapResult.yml" sourcestartlinenumber="1">If the vertex has not snapped, the <xref href="ArcGIS.Desktop.Mapping.SnapResult.Layer" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.SnapResult.SnapLocation" data-throw-if-not-resolved="false"></xref> are null, <xref href="ArcGIS.Desktop.Mapping.SnapResult.SnapType" data-throw-if-not-resolved="false"></xref> is None and the <xref href="ArcGIS.Desktop.Mapping.SnapResult.ObjectID" data-throw-if-not-resolved="false"></xref> is -1.
If the vertex has snapped, the properties contain the snapping information.
If the vertex has snapped to the <xref href="ArcGIS.Desktop.Mapping.SnapType.Grid" data-throw-if-not-resolved="false"></xref>, the <xref href="ArcGIS.Desktop.Mapping.SnapResult.ObjectID" data-throw-if-not-resolved="false"></xref> is 0 for a grid intersection, 1 for grid line and 2 for grid inference.</p>


## Members

### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnapResult.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.Layer" data-throw-if-not-resolved="false"></xref> the vertex has snapped to.</p>


```csharp
public Layer Layer { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnapResult.yml" sourcestartlinenumber="1">Gets the ObjectID of the feature in the <xref href="ArcGIS.Desktop.Mapping.Layer" data-throw-if-not-resolved="false"></xref> the vertex has snapped to.</p>


```csharp
public long ObjectID { get; }
```
### SnapLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnapResult.yml" sourcestartlinenumber="1">Gets the location the vertex has snapped to as a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapPoint SnapLocation { get; }
```
### SnapType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnapResult.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.SnapType" data-throw-if-not-resolved="false"></xref> the vertex has snapped to.</p>


```csharp
public SnapType SnapType { get; }
```


