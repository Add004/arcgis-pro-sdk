# PointEventSourceOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Represents a configuration to create a dynamic feature class (<xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>) originating from point events using the dynamic
segmentation process.</p>


## Object Signature

```csharp
public sealed class PointEventSourceOptions : RouteEventSourceOptions
```


## Members

### PointEventSourceOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions" data-throw-if-not-resolved="false"></xref> class. Use this constructor to omit the field for storing locating
angles during the creation of a <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref> using the dynamic segmentation process.</p>


```csharp
public PointEventSourceOptions()
```
### PointEventSourceOptions(AngleType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions" data-throw-if-not-resolved="false"></xref> class. Use this constructor to include the field for storing locating
angles during the creation of a <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref> using the dynamic segmentation process.</p>


```csharp
public PointEventSourceOptions(AngleType angleType)
```
### AsMultiPointFeature

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Gets or sets the geometry type in the route event source. If true, point events will be treated as multipoint features. If false, point
events will be treated as point features.</p>


```csharp
public bool AsMultiPointFeature { get; set; }
```
### ComplementAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Gets or sets whether the complement of the angle should be written to the <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool ComplementAngle { get; set; }
```
### HasAngleField

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Gets whether a field to store locating angles will be added to the <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool HasAngleField { get; }
```


