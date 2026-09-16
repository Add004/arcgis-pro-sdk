# GeodatabaseTopologyProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties.yml" sourcestartlinenumber="1">A class representing a geodatabase topology.</p>


## Object Signature

```csharp
public sealed class GeodatabaseTopologyProperties : TopologyProperties
```


## Members

### ClusterTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties.yml" sourcestartlinenumber="1">Gets the cluster tolerance for the topology.</p>


```csharp
public double ClusterTolerance { get; }
```
### GetTopologyDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties.yml" sourcestartlinenumber="1">Gets the topology definition.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TopologyDefinition GetTopologyDefinition()
```
### TopologyLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties.yml" sourcestartlinenumber="1">Gets the topology layer for the topology.</p>


```csharp
public ITopologyLayerContainer TopologyLayer { get; }
```
### WorkspaceName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GeodatabaseTopologyProperties.yml" sourcestartlinenumber="1">Gets the workspace name for the topology.</p>


```csharp
public string WorkspaceName { get; }
```


