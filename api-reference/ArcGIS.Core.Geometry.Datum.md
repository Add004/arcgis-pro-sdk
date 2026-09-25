# Datum

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Describes the horizontal datum of a geographic coordinate system or the vertical datum of a vertical coordinate system.
It is returned from <xref href="ArcGIS.Core.Geometry.SpatialReference.Datum" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.VerticalCoordinateSystem.Datum" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class Datum
```


## Members

### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the name of this horizontal datum.</p>


```csharp
public string Name { get; }
```
### SpheroidFlattening

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the flattening ratio of the spheroid of this horizontal datum.</p>


```csharp
public double SpheroidFlattening { get; }
```
### SpheroidName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the name of the spheroid of this horizontal datum.</p>


```csharp
public string SpheroidName { get; }
```
### SpheroidSemiMajorAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the length of the semi-major axis of the spheroid of this horizontal datum.</p>


```csharp
public double SpheroidSemiMajorAxis { get; }
```
### SpheroidSemiMinorAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the length of the semi-minor axis of the spheroid of this horizontal datum.</p>


```csharp
public double SpheroidSemiMinorAxis { get; }
```
### SpheroidWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the well-known ID of the spheroid of this horizontal datum.</p>


```csharp
public int SpheroidWkid { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Gets the well-known ID of this horizontal datum.</p>


```csharp
public int Wkid { get; }
```


