# ParcelFabric

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Parcels.html">Parcels</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Represents a parcel fabric.</p>


## Object Signature

```csharp
public sealed class ParcelFabric : Dataset, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">This class is used to</p>
<ul><li>Get parcel fabric related classes</li><li>This class is used to Create and delete parcel types</li><li>Get parcel topology</li><li>Get other parcel fabric classes Objects</li></ul>
<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="5">Objects of this class are obtained by calling <xref href="ArcGIS.Core.Data.Geodatabase.OpenDataset%60%601(System.String)" data-throw-if-not-resolved="false"></xref></p>


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Parcels.ParcelFabricDefinition" data-throw-if-not-resolved="false"></xref> object that describes this parcel fabric.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ParcelFabricDefinition GetDefinition()
```
### GetParcelTopology()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Returns the topology for the parcel fabric. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Topology GetParcelTopology()
```
### GetParcelTypeInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Returns all parcel type names, related feature classes and administration type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<ParcelTypeInfo> GetParcelTypeInfo()
```
### GetSystemTable(SystemTableType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Opens the specified parcel fabric system table.</p>


```csharp
public Table GetSystemTable(SystemTableType systemTableType)
```
### IsSystemTableSupported(SystemTableType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Gets a value indicating whether the system table specified by <code class="paramref">systemTableType</code> is supported
by the current <xref href="ArcGIS.Core.Data.Parcels.ParcelFabricDefinition.GetSchemaVersion" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsSystemTableSupported(SystemTableType systemTableType)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabric.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```


