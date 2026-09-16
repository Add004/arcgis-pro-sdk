# SpatialIndexDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.SpatialIndexDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a spatial <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SpatialIndexDescription : IndexDescription
```


## Members

### SpatialIndexDescription(FeatureClassDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.SpatialIndexDescription.yml" sourcestartlinenumber="1">Creates a description object of the spatial <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SpatialIndexDescription(FeatureClassDescription featureClassDescription)
```
### SpatialIndexDescription(Index, FeatureClassDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.SpatialIndexDescription.yml" sourcestartlinenumber="1">Creates a description object of the spatial <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialIndexDescription(Index spatialIndex, FeatureClassDescription featureClassDescription)
```
### SpatialIndexDescription(string, FeatureClassDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.SpatialIndexDescription.yml" sourcestartlinenumber="1">Creates a description object of the spatial <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialIndexDescription(string IndexName, FeatureClassDescription featureClassDescription)
```
### FeatureClassDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.SpatialIndexDescription.yml" sourcestartlinenumber="1">The description object representing the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> that will hold the spatial index.</p>


```csharp
public FeatureClassDescription FeatureClassDescription { get; }
```


