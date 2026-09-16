# VoxelLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a voxel layer.</p>


## Object Signature

```csharp
public class VoxelLayerCreationParams : LayerCreationParams
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Use the static VoxelLayerCreationParams.Create() method overloads to create a
VoxelLayerCreationParams instance.</p>


## Members

### Alignment

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Gets or sets the voxel alignment.</p>


```csharp
public VoxelAlignment Alignment { get; set; }
```
### Create(CIMVoxelDataConnection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Create a VoxelLayerCreationParams using the given CIMVoxelDataConnection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static VoxelLayerCreationParams Create(CIMVoxelDataConnection dataConnection)
```
### Create(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Create a VoxelLayerCreationParams using the data source at the given uri.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static VoxelLayerCreationParams Create(string uri)
```
### SetDefaultVariable(VoxelVariableCreationParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Sets the default variable profile after the layer creation. Any current default is cleared.</p>


```csharp
public void SetDefaultVariable(VoxelVariableCreationParams variable)
```
### Variables

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayerCreationParams.yml" sourcestartlinenumber="1">Gets the list of variables available for the Voxel layer.</p>


```csharp
public IReadOnlyList<VoxelVariableCreationParams> Variables { get; }
```


