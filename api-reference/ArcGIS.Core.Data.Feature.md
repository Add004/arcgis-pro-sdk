# Feature

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Represents a feature in a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class Feature : Row, IDisposable
```


## Members

### GetOriginalValue(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Gets the original value of a field at the given index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override object GetOriginalValue(int index)
```
### GetShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Gets the geometry of this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry GetShape()
```
### GetTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Gets the parent <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> of this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetTable()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its index position.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override object this[int index] { get; set; }
```
### SetShape(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Sets the geometry of this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShape(Geometry shape)
```
### Split(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Feature.yml" sourcestartlinenumber="1">Splits a polyline or polygon into multiple parts from the provided split geometry location with a system-assigned object ID.</p>


```csharp
public IReadOnlyList<long> Split(Geometry splitGeometry)
```


