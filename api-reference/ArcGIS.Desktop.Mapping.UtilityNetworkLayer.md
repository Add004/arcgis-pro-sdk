# UtilityNetworkLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.UtilityNetworkLayer.yml" sourcestartlinenumber="1">Represents a utility network dataset.</p>


## Object Signature

```csharp
public sealed class UtilityNetworkLayer : CompositeLayerWithTables, IMetadataInfo, IMetadataSource, ILayerContainer, IStandaloneTableContainer
```


## Members

### GetNamedTraceConfigurations()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.UtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets all of the named trace configurations within the utility network layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NamedTraceConfiguration> GetNamedTraceConfigurations()
```
### GetUtilityNetwork()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.UtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets utility network associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public UtilityNetwork GetUtilityNetwork()
```
### UNVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.UtilityNetworkLayer.yml" sourcestartlinenumber="1">Gets the Utility Network layer version.</p>


```csharp
public int UNVersion { get; }
```


