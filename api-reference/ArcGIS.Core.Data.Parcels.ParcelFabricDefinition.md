# ParcelFabricDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Parcels.html">Parcels</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabricDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a parcel fabric.</p>


## Object Signature

```csharp
public sealed class ParcelFabricDefinition : Definition, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabricDefinition.yml" sourcestartlinenumber="1">ParcelFabricDefinition objects can be obtained by calling <xref href="ArcGIS.Core.Data.Parcels.ParcelFabric.GetDefinition" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabricDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetSchemaVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabricDefinition.yml" sourcestartlinenumber="1">Gets the version number of the parcel fabric schema. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetSchemaVersion()
```
### GetTopologyEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Parcels.ParcelFabricDefinition.yml" sourcestartlinenumber="1">Gets if the topology is enabled on parcel fabric. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetTopologyEnabled()
```


