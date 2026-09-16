# ServiceCompositeSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Represents a service composite sub layer.</p>


## Object Signature

```csharp
public sealed class ServiceCompositeSubLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Gets the layer's definition which is null for composite service sublayers.</p>


```csharp
public override CIMBaseLayer GetDefinition()
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Sets the display name for the layer, however this method is not supported for this layer type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override void SetName(string newName)
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceCompositeSubLayer.yml" sourcestartlinenumber="1">Gets whether the ServiceCompositeSubLayer supports metadata</p>


```csharp
public override bool SupportsMetadata { get; }
```


