# FeatureClassDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class FeatureClassDefinition : TableDefinition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the dataset type.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetAreaField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the field containing the area of the shape.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAreaField()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetLengthField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the field containing the length of the shape.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetLengthField()
```
### GetShapeField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the field where the shape (geometry) is stored.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetShapeField()
```
### GetShapeType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.GeometryType" data-throw-if-not-resolved="false"></xref> for the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GeometryType GetShapeType()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> for the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetSplitModel()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.SplitModel" data-throw-if-not-resolved="false"></xref> of the feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SplitModel GetSplitModel()
```
### HasM()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this feature class supports storing measure(M) information with its shapes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasM()
```
### HasSpatialIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this feature class has a spatial index.</p>


```csharp
public bool HasSpatialIndex()
```
### HasZ()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this feature class supports storing vertical(Z) information with its shapes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasZ()
```
### IsCOGOEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClassDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this feature class is COGO (Coordinate Geometry) enabled.</p>


```csharp
public bool IsCOGOEnabled()
```


