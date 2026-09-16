# TopologyLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a topology layer with pre-defined properties.</p>


## Object Signature

```csharp
public class TopologyLayerCreationParams : LayerCreationParams
```


## Members

### TopologyLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TopologyLayerCreationParams(CIMDataConnection dataConnection)
```
### TopologyLayerCreationParams(Topology)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TopologyLayerCreationParams(Topology topology)
```
### TopologyLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TopologyLayerCreationParams(Item item)
```
### TopologyLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TopologyLayerCreationParams(Uri uri)
```
### AddAssociatedLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets whether the topology associated layers are to be added along with the topology layer. Default value is true.</p>


```csharp
public bool AddAssociatedLayers { get; set; }
```
### Topology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Topology Topology { get; protected set; }
```


